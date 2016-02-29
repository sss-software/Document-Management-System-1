[![Travis Ci](https://img.shields.io/travis/andela-rekemezie/Document-Management-System/develop.svg)](https://travis-ci.org/andela-rekemezie/Document-Management-System)
[![Coveralls](https://img.shields.io/coveralls/andela-rekemezie/Document-Management-System.svg)](https://coveralls.io/github/andela-rekemezie/Document-Management-System)
# DocKip

DocKip is a custom document magement system built with Express, Node, and Mongodb. The application allows you to manage users, roles and documents with assigned authorization. Basically, it helps your to create, share and management documents with easy. 

## Installation

1. Download and install [**Node JS**](https://nodejs.org/en/) if not already installed.
2. Download and install [**Mongodb**](https://www.mongodb.org/downloads/) if not already installed.
3. Clone the [**repository here**](hhttps://github.com/andela-rekemezie/Document-Management-System.git) or go to the project github page [**here**](https://github.com/andela-rekemezie/Document-Management-System) and download the zip file of the project. Unzip it.
4. Navigate to your terminal and change your directory to the **Document-Manager-REST-API**.
5. Run `npm install` to install node dependencies.
6. Run `bower install` to install frontend dependencies
7. Run `npm run initDb` to initialize your database with a role.

### Project Management
Checkout [Pivotal tracker](https://www.pivotaltracker.com/n/projects/1515820)

### Usage
The application allows for the SuperAdmin to manage the entire process and assign authorization for different roles.
Run `npm install gulp -g`
Run `gulp` on your terminal.
Navigate to `http://localhost:5555` on your browser.

### Test
Run `gulp test` on your terminal. Remember to  run test on the project root directory.

### Contributing
1. Create an issue. First look through [the open issues](https://github.com/andela-rekemezie/Document-Management-System/issues).
2. Clone the repository or fork it.
3. Create your feature branch: `git checkout -b my-new-feature`
5. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin your-new-feature`
5. Submit a pull request.

###  Links
* Follow me on [twitter](https://twitter.com/EkemezieRowland).
* [CLI version of Document manager with mongodb](https://github.com/andela-rekemezie/DMS-Mongoose).
* [CLI version of Document manager with PostgreSQL](https://github.com/andela-rekemezie/DMS-Sequelize).
* [Document-REST-API](https://github.com/andela-rekemezie/Document-Manager-REST-API)