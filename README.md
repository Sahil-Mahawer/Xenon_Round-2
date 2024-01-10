# Online Archive

A MERN stack app to keep track of online stuff, which you may want to view later.

## Demo

[Deployed on Netlify (front-end) & Heroku (back-end)](https://toviewlist.netlify.app)

## Built using

#### Front-end

- [ReactJS](https://reactjs.org/) - Frontend framework
- [Context API using useContext & useReducer hooks](https://reactjs.org/docs/context.html) - For state management
- [React Router](https://reactrouter.com/) - For general routing & navigation
- [Material-UI w/ lots of CSS customisations](https://material-ui.com/) - UI library

#### Back-end

- [Node.js](https://nodejs.org/en/) - Runtime environment for JS
- [Express.js](https://expressjs.com/) - Node.js framework, makes process of building APIs easier & faster
- [MongoDB](https://www.mongodb.com/) - Database to store document-based data
- [Mongoose](https://mongoosejs.com/) - MongoDB object modeling for Node.js
- [JSON Web Token](https://jwt.io/) - A standard to secure/authenticate HTTP requests
- [Bcrypt.js](https://www.npmjs.com/package/bcryptjs) - For hashing passwords
- [Validator.js](https://www.npmjs.com/package/validator) - For validation of JSON data
- [Mongoose Unique Validator](https://www.npmjs.com/package/mongoose-unique-validator) - Plugin for better error handling of unique fields within Mongoose schema
- [Dotenv](https://www.npmjs.com/package/dotenv) - To load environment variables from a .env file

## Features

- Authentication (login/register with email-password)
- Add/update/delete entries
- Add title, link, description, tags & type of link
- Bookmark important stuff (by 'starring' it)
- Mark the already read/watched items as 'viewed'
- Search entries by title, description or tags
- Filter entries by type (article, video or other), or by starred or viewed
- Click on tags to show all entries containing the tag you clicked on.
- Sort entries by oldest first, newest first, A-Z (alphabetical) or Z-A (reverse alpha.)
- Toast notifications for actions such as adding new entry, or 'starring' it etc.
- Dark mode toggle w/ local storage save
- Responsive UI for all screens

## Usage

#### Env variable:

Create a .env file in server directory and add the following:

```
MONGODB_URI = "Your Mongo URI"
PORT = 3005
SECRET = "Your JWT secret"

```

#### Client:

Open client/src/backendUrl.js & change "backend" variable to `"http://localhost:3005"`

```
cd client
npm install
npm start
```

#### Server:

Note: Make sure that you have installed 'nodemon' as global package.

```
cd server
npm install
npm run dev
```

## Screenshot

###  Login Page
![Check Your Internet Connection](https://ibb.co/QJKWXkg)
[Click to view image if above image is not visible](https://ibb.co/QJKWXkg)

### Register
![Check Your Internet Connection](https://ibb.co/mTkqcKC)
[Click to view image if above image is not visible](https://ibb.co/mTkqcKC)

### Home Page
![Check Your Internet Connection](https://ibb.co/ggX5CrY)
[Click to view image if above image is not visible](https://ibb.co/ggX5CrY)



