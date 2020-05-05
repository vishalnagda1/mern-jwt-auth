# MERN Auth (Backend)

[![GitHub license](https://img.shields.io/github/license/vishalnagda1/mern-jwt-auth?style=plastic)](https://github.com/vishalnagda1/mern-jwt-auth/blob/master/LICENSE) [![Repository version](https://img.shields.io/badge/version-1.0.0-brightgreen?style=plastic)](https://github.com/vishalnagda1/mern-jwt-auth/releases/tag/v1.0.0)


This is a Backend of a minimal full-stack login/authorization app using the `MERN` stack (`MongoDB` for our database, `Express` and `Node` for our backend, and `React` for our frontend). Also integrate `Redux` for state management for our `React` components.

**MERN Auth app will allow users to**

- Register
- Log in
- Access protected pages only accessible to logged in users
- Stay logged in when they close the app or refresh the page
- Log out

## Requirements

##### **Prerequisites**

You should have at least a basic understanding of fundamental programming concepts and some experience with introductory [`HTML`](https://developer.mozilla.org/en-US/docs/Web/HTML)/[`CSS`](https://developer.mozilla.org/en-US/docs/Learn/CSS)/[`Javascript`](https://developer.mozilla.org/en-US/docs/Web/JavaScript). And the knowledge of `MERN` stack  ([`Mongo`](https://university.mongodb.com/), [`Express`](https://expressjs.com/), [`React`](https://reactjs.org/), [`Node`](https://nodejs.dev/)) is an advantage.

##### **Install**

Lastly, make sure you have the following installed.

- Latest version of [Node.js](https://nodejs.org/en/)
- Latest version of [NPM (Node Package Manage)](https://www.npmjs.com/get-npm)
- Latest version of [MongoDB](https://docs.mongodb.com/manual/administration/install-community/)
- Latest version of [git](https://git-scm.com/) (**This is optional. It requires only if you choose to clone project**)

### Getting Started

1. Either you can **clone** or **download** repository from GitHub.

   - Clone with HTTPS *(required [git](https://git-scm.com/) installed in your system)*

     ```shell
     git clone https://github.com/vishalnagda1/mern-jwt-auth.git
     ```

   - Clone with SSH *(required [git](https://git-scm.com/) installed in your system)*

     ```sh
     git clone git@github.com:vishalnagda1/mern-jwt-auth.git
     ```

   - [Download Zip](https://github.com/vishalnagda1/mern-jwt-auth/archive/master.zip)

2. Navigate to project directory in the terminal or command prompt.

   ```shell
   cd mern-jwt-auth
   ```

3. Install project dependencies

   ```shell
   npm i
   ```

4. Create a `keys.js` file in `config` directory

   ```shell
   cp config/keys.sample.js config/keys.js
   ```

   **Note:** update `keys.js` file variables as per the requirements.

5. Run the project

   ```shell
   npm start
   ```

6. Your server is running at [http://localhost:5000](http://localhost:5000)



#### Backend APIs

1. Register

   - Endpoint - `/api/users/register`

   - HTTP Method - POST

   - Payload

     ```json
     {
         "name": "Vishal",
         "email": "test@test.com",
         "password": "test123",
         "password2": "test123"
     }
     ```

2. Login

   - Endpoint - `/api/users/login`

   - HTTP Method - `POST`

   - Payload

     ```json
     {
     	"email": "test@test.com",
     	"password": "test123"
     }
     ```



#### Contributing

1. Fork it ( https://github.com/vishalnagda1/mern-jwt-auth/fork )
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create a new pull request.
