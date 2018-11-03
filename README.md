# Running locally

To run the site locally you will need node and npm installed on your computer, to install / check if already installed follow the guidelines here:

[https://blog.teamtreehouse.com/install-node-js-npm-mac](https://blog.teamtreehouse.com/install-node-js-npm-mac)

Clone the project repo over here [https://github.com/niall-quinn/s2n-site](https://github.com/niall-quinn/s2n-site)

``git clone [https://github.com/niall-quinn/s2n-site.git](https://github.com/niall-quinn/s2n-site.git)``

Navigate to project directory

``cd s2n-site/``

and follow the steps below to run locally

# Static

A minimal setup for writing a static site, includes cache busting, minification, es6 Support and Sass with Webpack.

``npm i``


## Web Development
You'll need nodemon to run in development mode
```npm i nodemon -g```


```npm run dev```

Go to [http://localhost:8080/](http://localhost:8080/) in your browser

## Web Build for production

```npm start```

This will bundle and deploy files to /build which can be run with pretty much any server setup.

**/webpack**

Webpack configs are used in our package.json scripts to either bundle our app for development or deploy minified/cachebusted files to **/build** to be used in production.