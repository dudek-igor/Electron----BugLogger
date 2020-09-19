## Hello :wave:

### BugLogger

> CRUD app to track logs which uses React + Electron and MongoDB

### Dev

```bash
1.  Clone Repo
2.  Install - `npm install`
3.  Add your datebase - `Create .env file in the root directory of your project.Add variables DB_CONFIG=<yourDatabase>`
4.  Check app `npm start`
5.  Before build app, change in 'config/db.js', process.env.DB_CONFIG to connection string from datebase.
Without this app dont run after package.
6.  In package.json, in postpackage script change your platform, icon and arch if you are on Windows or Linux
7.  Build - 'npm run package'
8.  Enjoy
```

### Used:

- Electron-react-webpack-boilerplate - Alex Devero's,
- React Bootstrap,
- Bootstrap,
- Moment.js
- Dotenv
- MongoDB
- Mongoose

### License

ISC
