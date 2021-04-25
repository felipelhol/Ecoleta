<p align="center">
   <img src="mobile/src/assets/logo.png" width="200"/>
</p>


# Ecoleta

[![Author](https://img.shields.io/badge/author-Felipe%20Lima-red)](https://github.com/felipelhol)

> Project developed based on international environment week. This software provide a flow to create recyclable garbage collection points and show in a map around you.


<br />
<p align="center"><img src="gifecoletaweb.gif?raw=true"/></p>

> You can make the world better by sending materials to collection points and preserving the environment without waste!!!


<br />
<p align="center"><img src="mobilefinal.jpg?raw=true"/></p>

# :pushpin: Table of Contents

This project was developed on the Next Level Week event by [Rocketseat](https://rocketseat.com.br/) &nbsp;🚀💜

* [Requirements](#computer-requirements)
* [Installation](#round_pushpin-installation)
* [Getting Started](#runner-getting-started)
* [FAQ](#sos-faq)
* [License](#closed_book-license)


##  Getting started

# :computer: Requirements

**You need to install [Node.js](https://nodejs.org/en/download/) and [Yarn](https://yarnpkg.com/) or [npm](https://www.npmjs.com/) first and [Expo](https://expo.io/)

# :round_pushpin: Installation

Then in order to clone the project via HTTPS, run this command:
```
git clone https://github.com/felipelhol/Ecoleta.git
```

SSH URLs provide access to a Git repository via SSH, a secure protocol. If you have a SSH key registered in your Github account, clone the project using this command:

```
git clone git@github.com:felipelhol/Ecoleta.git
```

**Install dependencies**

```
yarn install

yarn add sqlite3

yarn add knex
```

# :runner: Getting Started

**Manually setup**

Run the following command in order to start the application in a development environment:

**Follow the steps below**

### Backend

```bash
# Starting from the project root folder, go to server folder
$ cd server

# Install the dependencies
$ yarn

# Use the script to run the migrations
$ yarn knex:migrate

# Use the script to run the seeds
$ yarn knex:seed

# To finish, run the api service
$ yarn dev:server

# Well done, project is started!
```

### Web

_Obs.: Before to continue, be sure to have the API running_

```bash
# Starting from the project root folder, go to frontend web folder
$ cd web

# Install the dependencies
$ yarn

# Be sure the file 'src/services/api.ts' have the IP to your API

# Start the client
$ yarn start
```

### Mobile

_Obs.: Before to continue, be sure to have the API running_

```bash
# Starting from the project root folder, go to mobile folder
$ cd mobile

# Install the dependencies
$ yarn

# Be sure the file 'src/services/api.ts' have the IP to your API

# Start the expo service and scan the QR code with Expo Client
$ yarn start
```


#  :sos: Faq

**Question:** What are the tecnologies used in this project?

**Answer:** The tecnologies used in this project are [NodeJS](https://nodejs.org/en/) + [Express Framework](http://expressjs.com/en/) to handle the server, + [ReactJS](https://reactjs.org/) + [React Native](https://reactnative.dev/) + [TypeScript](https://www.typescriptlang.org/) + [React Leaflet](https://react-leaflet.js.org/) + [Expo](https://expo.io/) + [Knex](http://knexjs.org/) + [SQLite](https://www.sqlite.org/) + [React Router DOM](https://reacttraining.com/react-router/) + [React Navigation](https://reactnavigation.org/) + [React Icons](https://react-icons.netlify.com/#/) + [EditorConfig](https://editorconfig.org/)
##

# 	:exclamation: Issues

Feel free to **file a new issue** with a respective title and description on the the [Ecoleta](https://github.com/felipelhol/.../issues) repository. If you already found a solution to your problem, **i would love to review your pull request**! 

# :closed_book: License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Released in 2020.
Made with love by [Felipe Lima](https://github.com/felipelhol) 👏🚀
[See my linkedin](https://www.linkedin.com/in/felipe-holanda-198224128/)
