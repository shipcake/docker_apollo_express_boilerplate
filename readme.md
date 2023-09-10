Boilerplate Mongodb + Firebase Authentication + Apollo Server Typescript

<b>I prepare Project Has <b>

- Sample Docker Compose File
- Visual Studio Code Configulation To Open In Dev Container.

<b>Modules</b>

- Modemon For Development With Auto Restart Server.
- Basic JWT GraphQL Authentication Verify.
- Basic JWT API Authentication Verify.
- Nginx (Prepare In Project Ready To Use)
- Typescript Ready To Use.
- Graphql Compression Size.
- Apollo Server V.4
- Graphql Upload Server V5 (I try to upgrade V6 but modules has error functional in now.)
- Firebase Authentication V.10
- Mongo Connection Service

<b>**_ Prepare Project _**<b>

1. Download Repo.
2. In Docker Command Line <code>docker create network custom_db</code>
3. Go To Firebase Create Project And Get Authentication Key Into File /backend/firebasecoinfig.ts <url>https://medium.com/@jantapa/%E0%B8%81%E0%B8%B2%E0%B8%A3%E0%B8%97%E0%B8%B3-login-page-%E0%B8%94%E0%B9%89%E0%B8%A7%E0%B8%A2-firebase-authentication-%E0%B9%83%E0%B8%99-reactjs-%E0%B9%81%E0%B8%9A%E0%B8%9A-step-by-step-%E0%B8%A5%E0%B8%B0%E0%B9%80%E0%B8%AD%E0%B8%B5%E0%B8%A2%E0%B8%94%E0%B8%A2%E0%B8%B4%E0%B8%9A-e890b41ce651</url>
4. Go To Firebase Console Setting And Get Service Key Into File /backend/serviceAccountKey.json <url>https://clemfournier.medium.com/how-to-get-my-firebase-service-account-key-file-f0ec97a21620</url>
5. Run MongoDB Compose File In database Folder.
6. Create MongoDB User And Replace URL Connection String Into File /.env "MONGOOSE_CONNECT=XX"
7. Run Project File docker-compose.dev.yml Ternimal In Visual Studio Code.

\*\* This Project Not Include Mongoose Library. Must Integrate Yourself.
