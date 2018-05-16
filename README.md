# Friend Finder - Node and Express Servers

"FriendFinder" is a compatibility-based application -- basically a dating app. This full-stack site will take in results from users' surveys, then compare their answers with those from other users. The app will then display the name and picture of the user with the best overall match.

## Demo
	
*Friend Finder* is deployed to Heroku. Please check it out [here](https://gentle-stream-65874.herokuapp.com/).

## Installation

To install the application follow the instructions below:

	git clone git@github.com/abemco/Friend-Finder.git
	cd friend-finder
	npm install
	
## Running Locally

To run the application locally and access it in your browser, first set the `PORT` environment variable to the value of your choice. An example is shown below.

	export PORT=3030
	
After the `PORT` environment variable has been set, run the Node.js application with the command below.

	node server.js
	
The application will now be running locally on `PORT`, in this case that is port 3030. You can then access it locally from your browser at the URL `localhost:PORT`, in this case `localhost:3030`.
