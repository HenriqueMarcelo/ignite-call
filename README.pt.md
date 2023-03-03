[English 🇬🇧](README.md)

## Ignite Call

"Ignite Call" é um projeto desenvolvido dentro do curso Ignite da Rocketseat que tem como objetivo criar uma aplicação para agendamentos online. O usuário informa os dias e horários que está disponível para agendamentos, e os clientes podem visualizar através de um calendário quais são os horários disponíveis para realizar o agendamento.

Para o agendamento, a aplicação utiliza a API do Google Agenda, onde o evento é criado pelo sistema. Após isso o horário no sistema será marcado como "ocupado", para que outros clientes não possam agendar nesse horário.

Durante o desenvolvimento, foram utilizados conceitos importantes, como: criação de uma aplicação com Next, utilização de Design System, integração com o Google Agenda, login com oAuth através do Google, criação de banco de dados com Prisma, manipulação de cookies com Next, transformação de dados com Zod, utilização de querys SQL com intervalos de datas, e muito mais.

O código fonte pode ser acessado através do link https://github.com/HenriqueMarcelo/ignite-call, enquanto a aplicação pode ser visualizada em https://ignite-call-alpha.vercel.app/. É importante ressaltar que a aplicação ainda **possui um bug a ser corrigido** para usuários que estão em fuso-horário diferente do servidor.

## Tecnologias utilizadas

Algumas das bibliotecas utilizadas para a construção do projeto foram:

- Next
- React
- Prisma
- React Hook Form
- Google APIs
- Next Auth
- Axios
- Dayjs
- Zod
- Next SEO

## Executando a aplicação

1. Clone o repositório
2. Instale as dependências utilizando o comando `npm install`
3. Copie o arquivo `.env.exemple` e crie um novo chamado `.env`
4. dentro do arquivo `.env` coloque a URL para o banco de dados, as credenciais para o Aplicativo do Google, e informe uma chamve para o NextAuth
5. Crie as tabelas do banco de dados utilizando o comando `npx prisma migrate dev`
6. Execute a aplicação utilizando o comando `npm run dev`

## Alguns comandos úteis

- `npx prisma init --datasource-provider SQLite`
- `npx prisma migrate dev`
- `npx prisma studio`
- `npx prisma db push`
