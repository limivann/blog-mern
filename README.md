<h1 align="center">
MERN Blog
</h1>
<p align="center">
MongoDB, Expressjs, React, Nodejs
</p>

> MERN is a fullstack implementation in MongoDB, Expressjs, React, Nodejs.

MERN stack is the idea of using Javascript/Node for fullstack web development.

## Clone or download

```terminal
$ git clone https://github.com/limivann/blog-mern.git
```

## Project Structure

```terminal
LICENSE
package.json
server/
   package.json
my-blog/
   package.json
...
```

# How to run

## Prerequisites

- [MongoDB](https://gist.github.com/nrollr/9f523ae17ecdbb50311980503409aeb3)
- [Node](https://nodejs.org/en/download/) ^16.3.0
- [npm](https://nodejs.org/en/download/package-manager/)

Notice: You need client and server runs concurrently in different terminal session, in order to make them talk to each other

## Client-side usage(PORT: 3000)

```terminal
$ cd my-blog  // go to client folder
$ npm install // npm install packages
$ npm start   // run it locally

// deployment for client app
$ npm run build
$ npm run start
```

## Server-side usage(PORT: 8000)

```terminal
$ cd server   // go to server folder
$ npm install // npm install packages
$ npm start   // run it locally
```

# Dependencies

| Client-side              | Server-side          |
| ------------------------ | -------------------- |
| react: ^17.0.2           | body-parser: ^1.19.0 |
| react-dom: ^17.0.2       | express: ^4.17.1     |
| react-router-dom: ^5.3.0 | mongodb: ^4.1.3,     |
| react-scripts: 4.0.3     | nodemon: "^2.0.14    |
| web-vitals: ^1.1.2       |
| whatwg-fetch: ^3.6.2     |

## Dev Dependencies

| Client-side           |
| --------------------- |
| autoprefixer: ^10.3.7 |
| npm-run-all: ^4.1.5   |
| postcss: ^8.3.9       |
| postcss-cli: ^9.0.1   |
| tailwindcss: ^2.2.17  |

<!-- # Screenshots of this project -->

<!-- User visit public and Home page
![User visit public and Home page](http://i.imgur.com/ORCGHHY.png) -->

## License

This project is licensed under the MIT License - see the LICENSE.md file for details

## Acknowledgments

Inspiration, code snippets, etc.

- [Frontend](https://github.com/desicoder2021/mern-blog-front)
- [Backend](https://github.com/desicoder2021/mern-blog-back)
