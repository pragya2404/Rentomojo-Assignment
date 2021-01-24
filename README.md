# PhoneBook

PhoneBook is a contact book application built using NodeJs + Express + Mongodb with CRUD operation.

<h4>Add Contact</h4>

![](static/crud1.gif)

<h4>Update and Delete</h4>

![](static/crud2.gif)

## Requirements

For development, you will only need Node.js and a node global package, Yarn, installed in your environement.

### Node
- #### Node installation on Windows

  Just go on [official Node.js website](https://nodejs.org/) and download the installer.
Also, be sure to have `git` available in your PATH, `npm` might need it (You can find git [here](https://git-scm.com/)).

- #### Node installation on Ubuntu

  You can install nodejs and npm easily with apt install, just run the following commands.

      $ sudo apt install nodejs
      $ sudo apt install npm

- #### Other Operating Systems
  You can find more information about the installation on the [official Node.js website](https://nodejs.org/) and the [official NPM website](https://npmjs.org/).

If the installation was successful, you should be able to run the following command.

    $ node --v

    $ npm --version

If you need to update `npm`, you can make it using `npm`! Cool right? After running the following command, just open again the command line and be happy.

    $ npm install npm -g

###
### Yarn installation
  After installing node, this project will need yarn too, so just run the following command.

      $ npm install -g yarn

---

## Dependencies

    "dependencies": {
        "body-parser": "^1.19.0",
         "express": "^4.17.1",
         "express-handlebars": "^4.0.4",
         "mongoose": "^5.9.16",
         "nodemon": "^2.0.4",
         "popups": "^1.1.3"
    }


## Install

    $ git clone https://github.com/Pragya2404/PhoneBook
    $ cd PhoneBook
    $ npm run server

---

