# Let Me Ask

![React](https://img.shields.io/badge/React-v17.0.2-blue)
![TypeScript](https://img.shields.io/badge/TypeScript-v4.3.5-blue)
![Firebase](https://img.shields.io/badge/Firebase-v9.1.0-orange)

O Let Me Ask é uma plataforma que permite aos streamers criar salas onde os espectadores podem fazer perguntas e votar nas que considerarem mais relevantes. A aplicação está sendo desenvolvida como um projeto ReactJS utilizando TypeScript e Firebase durante a Next Level Week #06 da Rocketseat.

## Funcionalidades

- [x] Criar sala de perguntas.
- [x] Fazer perguntas.
- [x] Votar nas perguntas mais relevantes.
- [x] Marcar perguntas como respondidas.
- [x] Destacar perguntas em destaque.

## Tecnologias Utilizadas

- React v17.0.2
- TypeScript v4.3.5
- Firebase v9.1.0

## Como Executar o Projeto

1. Clone o repositório:

```
git clone https://github.com/filipedower/let-me-ask.git
```

2. Instale as dependências:

```
npm install
```

3. Configure as credenciais do Firebase no arquivo `.env.local`:

```
REACT_APP_API_KEY=SuaChaveDeAPI
REACT_APP_AUTH_DOMAIN=SeuDominioDeAutenticacao
REACT_APP_DATABASE_URL=SuaURLdoBancoDeDados
REACT_APP_PROJECT_ID=SeuIDdoProjeto
REACT_APP_STORAGE_BUCKET=SeuBucketDeArmazenamento
REACT_APP_MESSAGING_SENDER_ID=SeuIDdeEnvioDeMensagens
REACT_APP_APP_ID=SeuIDdeAplicativo
```

4. Execute o projeto:

```
npm start
```

## Contribuição

Contribuições são bem-vindas! Para sugestões ou correções, por favor, abra uma issue primeiro para discutir o que você gostaria de mudar.

## Licença

Este projeto está licenciado sob a [MIT License](https://choosealicense.com/licenses/mit/).
