# project-for-webpack
1. run `npm init -y` to create package.json manually.
2. `mkdir dist` -> `cd dist` -> `touch index.html`
3. run `npm install --save-dev webpack webpack-dev-server webpack-cli` to install all the webpack related packages.<br/>
Note: You might need `npm cache clean -f` 
4. Update package.json->scripts->`start: "webpack-dev-server --config ./webpack.config.js --mode development"`<br/>
Note: In this command we tell we use `webpack-dev-server` with a `config` file called `./webpack.config.js` and mode would be development
5. Create `webpack.config.js`:<br/>
* entry: Where should webpack start looking from.
* 
6. run `npm install --save-dev babel-core babel-loader babel-preset-env`.
7. 