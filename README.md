# TaskED

## Live Demo [![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/fe63b30658e8a4322d0f#?env%5BTask%20Manager%20API%20(prod)%5D=W3sia2V5IjoidXJsIiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlfSx7ImtleSI6ImF1dGhUb2tlbiIsInZhbHVlIjoiIiwiZW5hYmxlZCI6ZmFsc2V9LHsia2V5IjoiYXV0aFRva2VuIiwidmFsdWUiOiIiLCJlbmFibGVkIjp0cnVlfV0=)

## Features

* Authentication & Authorization:
  
  * User login with username and password

  * Passwords are encrypted with bcrypt.
  
  * Users are authenticated via JWT (Bearer Token).
  
  * One cannot manage tasks and view user profile without being authenticated

  * One cannot edit or delete tasks created by other users

* Manage campground tasks with basic functionalities:

  * Create, edit and delete tasks

  * Upload photos

* Pagination support.

* Sorting and Filtering as per user's needs.


## Getting Started

> This app contains API secrets and passwords that have been hidden deliberately, so the app cannot be run with its features on your local machine. However, feel free to clone this repository if necessary.

* To run this app you need to use Postman (or any other client) to test out the project. Link is given in the documentation with everything set up for postman. Refer [Documentation](https://documenter.getpostman.com/view/5136546/TWDRszYT) for more info.

### Clone or download this repository

```sh
git clone https://github.com/sachingw777/TaskED.git
```


### Install dependencies

```sh
npm install
```

or

```sh
yarn install
```

## Built with

### Back-end

* [nodejs](https://nodejs.org/)
* [express](https://expressjs.com/)
* [mongoDB](https://www.mongodb.com/)
* [mongoose](http://mongoosejs.com/)
* [async](http://caolan.github.io/async/)
* [jwt](https://jwt.io/)
* [bcrypt](https://www.npmjs.com/package/bcrypt)
* [sendgrid](https://sendgrid.com/)

### Platforms

* [Heroku](https://www.heroku.com/)
* [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)

## License

#### [MIT](./LICENSE)
