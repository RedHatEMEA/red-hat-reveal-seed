red-hat-reveal-seed
===================

A seed project for reveal.js presentations in Red Hat

### Running locally

Some reveal.js features, like external markdown and speaker notes, require that presentations run from a local web server. The following instructions will set up such a server as well as all of the development tasks needed to make edits to the reveal.js source code.

1. Install [Node.js](http://nodejs.org/)

2. Install [Grunt](http://gruntjs.com/getting-started#installing-the-cli)

4. Clone the this repository
```sh
$ git clone https://github.com/RedHatEMEA/red-hat-reveal-seed.git
```

5. Install dependencies
```sh
$ npm install
```

6. Serve the presentation and monitor source files for changes
```sh
$ grunt serve
```

7. Open <http://localhost:8000> to view your presentation

There are 3 example presentations right now

http://localhost:8000/examples/RedHatForum2014_MWKeynote.html#/
http://localhost:8000/examples/fuse6.1.html#/

You can change the port by using `grunt serve --port 8001`.

### Running on OpenShift

Here is how to do this for yourself.

TODO - instructions in here

### Howto use Travis CI to automatically build and push this repository to OpenShift

When you push to your GitHub repository then Travis CI automatically executes a build and pushes and updates the application running on OpenShift.

TODO - instructions in here
