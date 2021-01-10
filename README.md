# MERN-stack
	First I need to create my backend
	I start with creating a folder especially made for backend purposes and at this time, I’m using Mongoose to create this for me
	Note: Developers will use backend as it’s own folder but for the sake of this simple project, I’ve placed it in the same folder as the frontend
  
	I have to make sure that I start with npm init-y, then install dependencies like cors, dotenv, express, mongoose
	Once they’re installed, I run nodemon server
	But wait, I have to go back on MongoDB, click the Connect button, and find the URI in there for my .env file. From there, I copy and paste the information, provide my Username and Password
  
	 Create some models of what you want to create. 
	Provide schema
	Require mongoose and Schema
	API input routes for CRUD operations, create, read, update, delete
	Provide a folder called routes
	Create js files inside folder (in this case, exercises and users)
	Add router, since its used to require certain purposes
	Require() any other functions that come to mind
	POST and GET requests for router.route
	Assign variables for these requests – like constructors
	A function .save to save these requests, .then and .catch
	Test POST and GET requests on insomnia application
	Use link http://localhost:5000/users/add and use POST
	Create json for the variables that you have, like username for example
	Add information to that variable name, like a username, ‘user added’
	Try GET request
	Hit Send
	You see information created as a json structure 
	Check MongoDB, you can see the users or variable names you’ve created, on Collections, tab
	If you see the information added, you can see that you’ve successfully added these requests
	Server.js needs to be edited for the ‘app.use’ function, due to the new js files added from routes
	Update (‘/update/:id’) and delete (router.route(‘/:id’).delete) as a part of the CRUD operations, will be added on the exercises.js 
  
	You can find information about the id via GET request
	Create your frontend (React)
	Add another terminal, npm install, npm start
	Understand the usage of ‘extends React.Component’
	Navigate to your src folder
	Go to index.html
	Look for ‘id=”root”
	This is telling you where the app is going to load
	We’re going to load our react app into that div
	Go to the js that loads with your html
	Create your file, starting point on App, to create your front end app from ‘./App’
	So we are loading, ReactDOM.render() our app from root
	Hot-reloads are made whenever these files are saved
	Add another terminal while npm start runs for React
	Npm install bootstrap
	Npm install react-router-dom
	Import BrowserRouter from react-router-dom
	Take note of the navbar in App.js, function App()
	Import all components in app.js, make sure you define the directories
	Note, since most components require React, component from ‘react’ and import Link, from ‘react-router-dom’, it is good to keep these two in mind when you are creating components
  
	Create a render() function
	Make sure you refer to the nav-links on there as well
	Create component files
	Create constructors for your component files
	Always call super when you’re defining constructor variables
	Create states
	onChangeUsername
	onChange(insert-variable-here)
	pass in variables here
	create .preventDefault() to prevent default html form from taking place
	in react, you can create single methods only if they’re going to be used in that method
	window.location = ‘/’ will take our users right back to the homepage after submitting
	we want to make sure what ‘this’ is referring to, ex. this.state – inherited from props
	to fix this, we will create binds above all of these onChange---( e ) functions, like this.onChangeDuration.bind(this)
	componentDidMount() is a react lifecycle method, it will call at different points in react
	set the state of your users array
  
	add standard form, possible to find on react website
	we add all forms to filfill the purpose of other functions/variables
	in this project, we are using datepicker so we have to npm install react-datepicker
	it will be used as our calendar selection
	we have to import the styling as well, which is the .css file
