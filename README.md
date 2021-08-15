# Preact Boilerplate

A minimal [Preact](https://preactjs.com) boilerplate project, powered by [Parcel](https://parceljs.org).

![Preact App in Action](https://user-images.githubusercontent.com/48409548/94948750-4707e680-04f9-11eb-99e9-eb53ed5b5c57.png)

## Folder Structure

No configuration or complicated folder structures, just the files you need to build your app:

```
preact-boilerplate
├── README.md
├── node_modules
├── package.json
├── .gitignore
├── public
│   ├── favicon.ico
│   └── index.html
└── src
    ├── App.css
    ├── App.js
    ├── index.css
    ├── index.js
    └── logo.svg
```

## Development

To get a local copy of the code, clone it using git:

```
git clone https://github.com/SafdarJamal/preact-boilerplate.git
cd preact-boilerplate
```

Make it your own:

```
rm -rf .git && git init && npm init
git add .
git commit -m "Initial commit"
```

Install dependencies:

```
npm i
```

Now, you can start a local web server by running:

```
npm start
```

And then open http://localhost:3000 to view it in the browser.

#### Available npm Scripts

| Script        | Description                                          |
| ------------- | ---------------------------------------------------- |
| npm start     | Runs the app in development mode.                    |
| npm run build | Builds the app for production to the `build` folder. |

## Credits

Preact Boilerplate is built and maintained by [Safdar Jamal](https://safdarjamal.github.io).

## License

This project is licensed under the terms of the [MIT license](https://github.com/SafdarJamal/preact-boilerplate/blob/master/LICENSE).
