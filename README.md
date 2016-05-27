#Webpack

The webpack-dev-server is a little node.js Express server which uses the webpack-dev-middleware to serve a webpacl bundle. It also has a little runtime which is connected to the server via Sockiet.IO. The server emits information about the complilation state to the client, which reacts to those events. You can choose between different modes, depending on your needs.

##Things you can expect to do with webpack:
	-Bundle Splitting
	-Async Loading
	-Packaging static assets like images and CSS.

##Why webpack?
You can split your application into multiple files, for example if you have a multiple pages in a single page application the user will only need to download code one time even if they decide to navigate to a different page.

Because webpack has the ability to build and bundle CSS, preprocessed CSS, compile to JavaScript languages, and imgages it replaces a multitude of other tools such as grunt, gulp, less, and sass. It also supports other favorite module systems such as Angular.js, ES6, AMD, and Common.js.
