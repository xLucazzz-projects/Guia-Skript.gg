## Instalação

Necessário NodeJS v15+

```bash
npm install

node .
```

## Configuração

```js
{
    "bot": {
        "token": "TOKEN DO BOT (https://discord.com/developers/applications)"
    },
    "mysql": {
        "database": "newWlBot",
        "database2": "vrp",
        "user": "USUÁRIO DE CONEXÃO AO MYSQL",
        "port": "3306",
        "host": "IP DE CONEXÃO DO MYSQL",
        "password": "SENHA DO USUÁRIO MYSQL"
    },

    "http": {
        "server_ip": "IP OU DOMÍNIO AQUI",
        "server_port": 3000
    },

    "whitelist": {
        "enabled": true,
        "whitelist_channel": "ID DO CANAL ONDE A WHITELIST VAI SER FEITA",
        "whitelist_logs": "ID DO CANAL ONDE SERÃO ENVIADAS AS WHITELISTS",
        "staff_role": "ID DO CARGO STAFF",
        "analysisRole": "ID DO CARGO ESPERANDO SER APROVADO",
        "waitingIDRole": "ID DO CARGO ESPERANDO LIBERAR ID",
        "resultsChannel": "ID DO CANAL ONDE SERÃO ENVIADOS OS RESULTADOS",
        "questions": [
            { "question": "O que é roleplay para você?", "type": 0 },
            { "question": "Se alguém apontasse uma arma para você, qual seria a reação do seu personagem?", "type": 0 },
            { "question": "Descreva as características positivas e negativas do seu personagem.", "type": 0 },
            { "question": "Três bandidos te param no meio da rua (você está sozinho) e anunciam um sequestro. O que você faz?", "type": 0 },
            { "question": "Você acaba de chegar na Cidade e encontra pessoas falando fora do roleplay. O que você faz?", "type": 0 },
            { "question": "Viaturas te cercam e tentam te abordar do nada. O que você faz?", "type": 0 },
            { "question": "Você acaba de sacar uma grande quantia no banco e percebe que veículos estão atrás de você. Então, premeditando o que irá acontecer. O que você faz?", "type": 0 },
            { "question": "Você foi morto em uma ação após discutir com um bandido. Mais tarde, você encontra o mesmo bandido, com as mesmas roupas, tatuagem e voz. O que faz?", "type": 0 },
            { "question": "Você encontra um médico/policial/mecânico folgado, de destratando e agindo de forma grosseira e hostil. O que faz?", "type": 0 },
            { "question": "Conte a HISTÓRIA do seu personagem: (Não envie links ou anexo nessa parte, mantenha no limite do discord de 4000 caracteres.", "type": 1 }
        ]
    },

    "removeWhitelist": {
        "enabled": true,
        "channel_logs": "ID DO CANAL ONDE SERÃO ENVIADAS AS LOGS"
    },

    "auto_role": {
        "enabled": true,
        "roleID": "ID DO CARGO QUE SERÁ ADICIONADO AO ENTRAR"
    },

    "ticket": {
        "enabled": true,
        "guild_id": "ID DO SERVIDOR",
        "channel_id": "ID DO CANAL ONDE SERÁ DEFINIDO O MENU",
        "channel_logs": "ID CANAL DE LOGS",
        "staff_role": "ID CARGO DA STAFF",
        "ticketCategories": [
            { "label": "Suporte", "value": "Suporte", "description": "Abra um ticket referente à suporte.", "emoji": "📁", "parentId": "ID DA CATEGORIA" },
            { "label": "Compras", "value": "Compras", "description": "Abra um ticket referente à transações realizadas.", "emoji": "💰", "parentId": "ID DA CATEGORIA" },
            { "label": "Denúncias", "value": "Denúncias", "description": "Abra um ticket referente à denúncias de jogadores e/ou membros da equipe.", "emoji": "🚫", "parentId": "ID DA CATEGORIA" }
        ]
    }
}
```

<center>Feito com ❤️ por xLucazzz</center>
