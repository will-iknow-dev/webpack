#Webpack

The webpack-dev-server is a little node.js Express server which uses the webpack-dev-middleware to serve a webpacl bundle. It also has a little runtime which is connected to the server via Sockiet.IO. The server emits information about the complilation state to the client, which reacts to those events. You can choose between different modes, depending on your needs.

##Things you can expect to do with webpack:
	-Bundle Splitting
	-Async Loading
	-Packaging static assets like images and CSS.

##Why webpack?
You can split your application into multiple files, for example if you have a multiple pages in a single page application the user will only need to download code one time even if they decide to navigate to a different page.

Because webpack has the ability to build and bundle CSS, preprocessed CSS, compile to JavaScript languages, and imgages it replaces a multitude of other tools such as grunt, gulp, less, and sass. It also supports other favorite module systems such as Angular.js, ES6, AMD, and Common.js.

##Setting up webpack for beginners
Project Requirements:
- Node.js
- NPM.js 
-	NPM Node Package Manager is a command line interface program to manage node.js libraries.
- I use Sublime Text 3 text editor but feel free to use whatever your comfortable with.

##Installing webpack
Open a command prompt and run:
	
-	$ npm install webpack -g

This makes the webpack pack command available.

##Setup the compilation
Open your document editor and create an empty directory.
Create these files:
	##add entry.js
	inside entry.js file write the following code:
	document.write("It works.");

	##add index.html
	<html>
	 <head>
	  <meta charset="utf-8">
	 </head>
	 <body>
	  <script type="text/javascript" src="bundle.js" charset="utf-8"></scrip	   t>
	 </body>
	</html>
Then run the following command in the command prompt:
	#$ webpack ./entry.js bundle.js
What this will do is compile your code and create a bundle file.

