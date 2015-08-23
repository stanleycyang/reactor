#Reactor

###Purpose

>To automate the setup an React + Flux + ES2015 application

###Dependencies

> nodeJS
> node package manager (npm)

###Features

- `webpack`
- `react`
- `flux`
- `react-router`

###Installation for Macs

  	$ curl https://raw.githubusercontent.com/syang019/reactor/master/reactor -O
	$ chmod 755 reactor
	$ sudo mv reactor /bin

###Usage

  	$ cd ~/Desktop
  	$ reactor HelloWorld
  	$ cd reactor
  	$ webpack-dev-server --hot --inline [or webpack to build]

Your `reactor` setup should now be working on `localhost:8080/webpack-dev-server`!

**Alternatively**

You can also set in your npm scripts (package.json)

	"start": "webpack-dev-server --hot --inline",
	"build": "webpack"

Which will run it on `npm start` and `npm run build`, respectively.
