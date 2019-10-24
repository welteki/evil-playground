## Welteki Playground

Just a simple playground that can be used for trying things out or just to
explain something to someone. Provides an environment set up to use JavaScript
that will auto run changes you make. Other features include a colorful logging
system, esm or commonjs imports/exports and tape set up for writing specs.

### Install

Clone this repo into your local system or generate a new repository using this as a template,
navigate to the folder and run:

```
$ npm run setup
```

This will install the dependencies for this project. After that finishes, you
should be good to go.

### Usage

There are two main use cases for this playground. Run some code or test some
code.

#### Run some code

To get started running some code, just run the following in the project root:

```
$ npm start
```

The initial 'Up and running' string should appear once started and you are good
to go. Now just edit the `index.js` file in the roots, and your code will be
executed on each save.

#### Test some code

Testing is set up with tape and linting done with eslint.
Specs live in the `test` directory and can be run in one of two ways, each with
it's own command.


##### Linting

The entire codebase can be checked using eslint by running the following:

```
$ npm run lint
```

##### One shot

Run the following to run all your specs in one go, exiting
afterwards:

```
$ npm test
```

##### Watch and run
If you would like to run the specs every time you make a change to the specs or
your units under test, just run:

```
$ npm run test:watch
```
