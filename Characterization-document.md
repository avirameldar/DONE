<div style="display: none;">

<style>
    H1, h3{
        color: lightBlue;
    }
    img{
        width: 100px;
    }
    #done{
        color: orange;
    }
</style>
</div>

![logo](./LOGO/done-logoDark.png)

# Welcom to 'DONE'

A simple and powerfull task management, that save your time, help you get in focus and make all your tasks - DONE.

App Name: <span id="done">DONE</span>

Devlopet and design by: Aviram Eldar.

Hacker-U, Final Project

### About

          Our task dispatch and management application revolutionizes the way teams collaborate and handle assignments. Designed with simplicity and efficiency in mind, this platform empowers managers to seamlessly dispatch tasks while providing users with the flexibility to pull challenges into their workspace.

## Technics:

### Backend - NodeJS, Express

### DataBase - MongoDB

### Frontend - ReactJS

<hr>

### Packages from NPM

#### Backend

- bcryptjs
- chalk
- cors
- crypto
- date-fns
- dotenv
- express
- fs
- joi
- jsonwebtoken
- lodash
- mongoose
- mongoose-sequence
- morgan
- nodemon
- path
- uuid

####

Frontend

- axios
- date-fns
- formik
- joi
- jwt-decode
- moment
- mui-material
- mui-icons-material
- react-icons
- reactjs-popup
- react-router-dom

<hr>
<br>

### How to Use

- When a user enters to the web-app, he get to the Welcome page.

- The user will have the ability to sign up, or login, If he already signed-up.

#### Regular User

    The regular user is able to:
    (On the Dashboard):
    - Read the tasks
    - Pull task
    - Search task
    - Toggle to dark mode
    (On the System Task):
    - Add task
    - Edit task
    - Make task completed
    - Restore task
    - Toggle between card view to list view
    - Sign out

#### Admin

    Only the admin is able in the dashboard to:
    - Create task
    - Edit tasks
    - Delete tasks

In order to enter as Admin you need to log-in with the user details:<br>
email: you@you.com <br>
password: Youyou1!

### .env:

    PORT = 5010
    LOGGER = "morgan"
    JWT_SECRET = "done23"
    DB = "MONGODB"
    ATLAS_USER_NAME = avirameldar
    ATLAS_PASSWORD = done
    MONGODB = mongodb+srv://avirameldar:done@cluster0.twlhtwx.mongodb.net
    ENVIRONMENT = "production"
    #ENVIRONMENT = "development"#* If we want to work with the local environment
    TOKEN_GENERATOR = "jwt"
    VALIDATOR = "Joi"

### config.json:

    {
    "apiUrl": "http://localhost:5010"
    }

<br><br><br><br>

### Enjoy

&copy; aviram.eldar@gmail.com
