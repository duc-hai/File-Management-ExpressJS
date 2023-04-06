# File Management

## Connect database and config
1. Install [mysql](https://www.mysql.com/downloads/) or [xampp](https://www.apachefriends.org/download.html) to connect db
2. Open mysql (xampp), create database file_management (or whatever name you like)
3. Import table into db file_management.sql `/src/repositories/file_management.sql`
4. Config host, user, password, db name at: `/.env`

## Run project
    node index.js
or `npm start` (Dev mode)

## Functions completed
- Register, login: save data into db (mysql2), hash password (bcrypt), cookie, session, validate data (express-validator), flash message...
- Express routers, rate limit
- Files management: CRUD files, folders, upload files (ajax), donwload file, folder (zip format)...