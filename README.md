# [Flask React Datta Able](https://appseed.us/product/flask-react-datta-able)

Open-source full-stack seed project coded in React and Flask on top of a modern design from CodedThemes. The **[Flask React](https://appseed.us/product/flask-react-datta-able)** codebase is already configured with an SQLite database, API (via **Flask-RextX**), and JWT token-based authentication flow. **Datta Able** is an open-source **React Dashboard** that provides a colorful and modern design. 

<br />

> Features

- Modern aesthetics UI design - Designed by [CodedThemes](https://bit.ly/37fF9RT)
- React, Redux, Redux-persist
- Authentication: JWT Login/Register/Logout
- Backend: [Flask API Server](https://github.com/app-generator/api-server-flask) 

<br />

> Links

- [Flask React Datta Able](https://appseed.us/product/flask-react-datta-able) - product page
- [Flask React Datta Able](https://flask-react-datta-able.appseed-srv1.com/) - LIVE Demo
- [Flask React Datta Able](https://docs.appseed.us/products/react/flask-datta-able) - product documentation
- Download Backend: [Flask API Server 📥](https://github.com/app-generator/api-server-flask/archive/refs/heads/main.zip)
- Donwnload Frontend: [React Datta Able 📥](https://github.com/app-generator/react-node-js-datta-able/archive/refs/heads/main.zip)  

<br >

> **Note**: This product can be used with other API Servers for a complete fullstack experience. **ALL API servers use an unified interface**

- [Django API Server](https://github.com/app-generator/api-server-django) - open-source product
- [Node JS API Server](https://github.com/app-generator/api-server-nodejs) - open-source product / Typescript / SQLite / TypeORM / Joy for validation
- [Node JS API Server PRO](https://github.com/app-generator/api-server-nodejs-pro) - **commercial product**
    - SQLite / TypeORM / Joy / Docker
    - MongoDB / Mongoose / Joy Docker (separate branch, same project)

<br />

![Flask React Datta Able - Open-source full stack product built in Flask and React.](https://user-images.githubusercontent.com/51070104/127129620-bae3b6b3-eb4f-4ad7-a694-5a3c1d6e37cb.png)

<br />

## Start Flask API Server

Simple starter built with Python / Flask-RestX / Sqlite3 and JWT Auth. The authentication flow is based on [json web tokens](https://jwt.io).

<br />

> How to use the code

**Clone the sources**

```bash
$ git clone https://github.com/app-generator/api-server-flask.git
$ cd api-server-flask
```

**Create a virtual environment**

```bash
$ virtualenv -p python3 venv
$ source venv/bin/activate
```

**Install dependencies** using pip

```bash
$ pip install -r requirements.txt
```

**Set up the environment** 

```bash
$ export FLASK_APP=run.py
$ export FLASK_ENV=development
```

The API server will start using the default port `5000`. 

<br />

## Start React UI 

To use the product Node JS (>= 12.x) is required and GIT to clone/download the project from the public repository.

**Step #1** - Clone the project

```bash
$ git clone https://github.com/app-generator/react-datta-able-dashboard.git
$ cd react-datta-able-dashboard
```

<br >

**Step #2** - Install dependencies via NPM or yarn

```bash
$ npm i
// OR
$ yarn
```

<br />

**Step #3** - Start in development mode

```bash
$ npm run start 
// OR
$ yarn start
```

<br />

## Configure the backend server

The product comes with a usable JWT Authentication flow that provides only the basic requests: login/logout/register. 

**API Server URL** - `src/config/constant.js` 

```javascript
const config = {
    ...
    API_SERVER: 'http://localhost:5000/api/'  // <-- The magic line
};
```

<br />

**API Server Descriptor** - POSTMAN Collection

The backend server uses an [Unified API defition](https://docs.appseed.us/boilerplate-code/api-server/api-unified-definition) maintained and actively supported by AppSeed across multiple frameworks: Flask, Node JS, FastAPI.

- [API POSTMAN Collection](https://github.com/app-generator/api-unified-definition/blob/main/api.postman_collection.json) - can be used to mock (simulate) the backend server or code a new one in your preferred framework. 

<br />

---
[Flask React Datta Able](https://appseed.us/product/flask-react-datta-able) - Provided by [CodedThemes](https://codedthemes.com/) and **AppSeed [App Generator](https://appseed.us/app-generator)**.
