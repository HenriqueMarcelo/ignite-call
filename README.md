[Português 🇧🇷](README.pt.md)

## Ignite Call

"Ignite Call" is a project developed within Rocketseat's Ignite course that aims to create an application for online scheduling. The user informs the days and times that he is available for appointments, and customers can view through a calendar which are the available times to make the appointment.

For scheduling, the application uses the Google Calendar API, where the event is created by the system. After that the time in the system will be marked as "busy", so that other customers cannot schedule at that time.

During the development, important concepts were used, such as: creation of an application with Next, use of Design System, integration with Google Calendar, login with oAuth through Google, database creation with Prisma, cookies handling with Next, data transformation with Zod, use of SQL queries with date ranges, and much more.

The source code can be accessed via the link https://github.com/HenriqueMarcelo/ignite-call, while the application can be viewed at https://ignite-call-alpha.vercel.app/. It is important to note that the application still **has a bug to be fixed** for users who are in a different time zone from the server.

## Technologies used

Some of the libraries used to build the project were:

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

## Running the application

1. Clone the repository
2. Install the dependencies using the `npm install` command
3. Copy the `.env.example` file and create a new one called `.env`.
4. inside the `.env` file enter the URL for the database, the credentials for the Google Application, and enter a call to NextAuth
5. Create the database tables using the `npx prisma migrate dev` command
6. Run the application using the `npm run dev` command

## Some useful commands

- `npx prisma init --datasource-provider SQLite`
- `npx prisma migrate dev`
- `npx prisma studio`
- `npx prisma db push` `npx prisma db push`

