# CPSC_473_Assignment9

How to run:
Open up terminal to /chattrbox
	npm run dev


Make a JSON file
	npm init

From the command line, install the ESLint tool with
	npm install -g eslint
	eslint --init
		Answer the config initialization wizard’s questions as follows:
		? How would you like to configure ESLint? ​Answer questions about your style
		? Are you using ECMAScript 6 features? ​No
		? Where will your code run? ​Browser
		? Do you use CommonJS? ​No
		? Do you use JSX? ​No
		? What style of indentation do you use? ​Spaces
		? What quotes do you use for strings? ​Single
		? Do you require semicolons? ​Yes
		? What format do you want your config file to be in? ​JSON



Make sure that these things are downloaded
	npm install --save-dev nodemon

	npm install -g wscat
	npm install --save ws //websockets

	npm install --save-dev browserify babelify watchify
	to test: 
		babel app/scripts/src/app.js -o app/scripts/dist/main.js
		npm run build
		npm run watch


Run the chat in different terminals
	wscar -c http://localhost:3001