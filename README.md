# Preact Boilerplate

A minimal Preact boilerplate project, powered by Parcel.

<p align="center">
  <img alt="Preact App in Action" src="https://user-images.githubusercontent.com/48409548/67021430-0c0a7880-f119-11e9-8031-cbc278164e4b.png">
</p>

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
    └── logo.png
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
```

Install dependencies:

```
npm i
```

Finally, you need to start a local web server. Run:

```
npm start
```

#### npm scripts

| Script        | Description                                          |
| ------------- | ---------------------------------------------------- |
| npm start     | Runs the app in the development mode.                |
| npm run build | Builds the app for production to the `build` folder. |

## License

This is an open source software [licensed as MIT](https://github.com/SafdarJamal/preact-boilerplate/blob/master/LICENSE).
