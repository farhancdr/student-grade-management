<h1 align="center">
Student grade management system
</h1>
<p align="center">
MongoDB, Expressjs, React/Redux, Nodejs
</p>

Keep track your students' grades easily! Built with Node.js, Express, MongoDB, and ReactJs.


# Features!

- Add / Update / Delete User
- Add / Update / Delete Lesson
- Add / Update / Delete Grades

### Tech

- [MongoDB](https://www.mongodb.com/) - A document-oriented, No-SQL database used to store the application data.
- [ExpressJS](https://expressjs.com/) - fast node.js network app framework.
- [nodeJS](https://nodejs.org/) - A JavaScript runtime built on Chrome's V8 JavaScript engine

### Installation

Requires [Node.js](https://nodejs.org/) to run.

Install the dependencies and devDependencies

```sh
$ git clone https://github.com/farhancdr/student-grade-management.git
$ yarn
```

### Database seeding
After installing all packages and dependencies, you can seed the database with some data.

```sh
$ node seed.js
```
> seed.js will auto generate some dummy users, lessons and grades. For Users creation faker npm package have been used!

Start the server.

```sh
$ yarn dev
```

## License

MIT
