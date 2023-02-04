# [Tools & co](https://toolsandco-ycuc.onrender.com/)

_Tools&Co gives people the ability to rent various tools and achieve their DIY dreams 🤩_

<div id="screenshot"><a href="https://toolsandco-ycuc.onrender.com/"><img src="./toolsandco-screenshot.png"></a></div>

Tools&Co is a FullStack web application made by [@bapturp](https://github.com/bapturp) [@hugoviolas](https://github.com/hugoviolas) and [@inesza](https://github.com/inesza) during the [Ironhack Web Development Bootcamp](https://www.ironhack.com/en/web-development) in only **4 days** 🚀

**Technologies used**

- Javascript
- HTML
- CSS
- Node
- Express
- Mongoose
- MongoDB

It implements 5 database models, full CRUD operations, sign up/login/logout, 3 differents user roles.

## Setup dev environment

### Dependencies

Install the following packages on your local machine:

- npm version 8
- node version 18
- mongodb version 6

### Clone repo

```sh
git clone https://github.com/bapturp/toolsandco.git
cd toolsandco/
```

### Setup the .env file

This project requires some environment variables to run, it reads the file `.env` on startup. An example file is provided `.env.example`.

**Environment variables:**

- `PORT`: Port on which the the website is accessible.
- `MONGODB_URI`: URI of the mongo database (i.e. `mongodb://127.0.0.1:27017/toolsharing`).
- `SESSION_SECRET`: Secret used to sign the session ID cookie, [see session doc](https://www.npmjs.com/package/express-session#user-content-secret).
- `CLOUDINARY_NAME`: Cloudinary name
- `CLOUDINARY_KEY`: Cloudinary key
- `CLOUDINARY_SECRET`: Cloudinary secret

### Install NodeJS dependencies

```sh
npm install
```

### Seed the database

Default data can be seed in the database:

```sh
npm run seed
```

### Start the project

```sh
npm run dev
```
