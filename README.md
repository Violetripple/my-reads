# MyReads Project

> [A Project App](https://my-reads-sewquuiczv.now.sh) implemented with [React](https://reactjs.org) and [React Router](https://github.com/ReactTraining/react-router) and bootstrapped with [Create React App](https://github.com/facebookincubator/create-react-app).

----

</br>

## Features

- Review books from different shelves: Currently Reading, Want to Read, Read;

- Move books between different shelves: Currently Reading, Want to Read, Read and None;

- Search books from resources based on Google Books API.

</br>

Click the bottom right `plus` icon to start searching most books, suggestions appears when typing. Just have fun!

----
</br>

## MyReads Project Folder Structure

Visit the project demo at this URL: [https://my-reads-sewquuiczv.now.sh](https://my-reads-sewquuiczv.now.sh).

```bash
├── README.md
├── package.json
├── public
│   ├── favicon.ico
│   ├── index.html
│   └── manifest.json
├── src
│   ├── App.css
│   ├── App.js
│   ├── App.test.js
│   ├── BooksAPI.js
│   ├── icons
│   │   ├── add.svg
│   │   ├── arrow-back.svg
│   │   └── arrow-drop-down.svg
│   ├── index.css
│   ├── index.js
│   └── registerServiceWorker.js
└── yarn.lock
```

----

</br>

## Getting started developing

- Branch and/or clone the repo locally.
- cd into it
- install all the require packages: `npm i`
- build the project: `npm run build`
- start the project: `npm start`

----
</br>

## Tech stacks used in this project

- React

- React Router

- Fetch API

Since the project is bootstrapped with create-react-app, please read its documentation details here: [Documentation](https://github.com/facebookincubator/create-react-app).

----
</br>

## Screenshot

![An awesome example image](screenshot/1.png)

----
</br>

## MyReads Project Description

[This project app](https://my-reads-sewquuiczv.now.sh) is a good example of using `Pure React`. what's more, in this app, I had heavily used the [new Context API](https://reactjs.org/docs/context.html) (rather than choosing [Redux](https://redux.js.org)) which I found quit useful and convenient.

I made all components under [React Strict Mode](https://reactjs.org/docs/strict-mode.html) but warning messages always appears since the [React Router](https://github.com/ReactTraining/react-router) itself didn't come up updating with the new react lifecycle.

Finally, this project is developed at the foundation of [reactnd-project-myreads-starter](https://github.com/udacity/reactnd-project-myreads-starter) which is very helpful. I had done my best to optimize the major part codes and made it more simple and readable.