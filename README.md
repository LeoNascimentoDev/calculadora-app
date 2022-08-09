# https://leonascimentodev.github.io/calculadora-app/

# After cloning the directory, in the project directory, you can run:

### `npm install`

## To run the application in your machine.

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\

### To Deploy

npm add -D gh-pages

In package.json, add:

"homepage": "https://yourgithubname.github.io/your-app-name",
"scripts": {
  "predeploy": "npm run build",
  "deploy": "gh-pages -d build",
},

Rotes
<BrowserRouter basename={process.env.PUBLIC_URL}>
// ...
</BrowserRouter> 

npm run deploy