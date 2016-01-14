# Sandbox

This README outlines the details of collaborating on this Ember application.
A short introduction of this app could easily go here.

## Start new App

* docker-compose up
* docker-compose run sandbox ember init
* sudo chown -R $USER:$USER sandbox

## Installation

* git clone git@github.com:azclick/yebo-ember.git ../yebo-ember
* git clone git@github.com:azclick/yebo-sdk.git ../yebo-sdk
* docker-compose build
* docker-compose run sandbox npm install
* docker-compose run sandbox bower install --allow-root

## Running / Development

* docker-compose up
* Visit your app at [http://localhost:4200](http://localhost:4200).

### Code Generators

Make use of the many generators for code, try `ember help generate` for more details

### Running Tests

* docker-compose run sandbox ember test
* docker-compose run sandbox ember test --server

### Building

* docker-compose run sandbox ember build
* docker-compose run sandbox ember build --environment production

### Deploying

Specify what it takes to deploy your app.

## Further Reading / Useful Links

* [ember.js](http://emberjs.com/)
* [ember-cli](http://www.ember-cli.com/)
* Development Browser Extensions
  * [ember inspector for chrome](https://chrome.google.com/webstore/detail/ember-inspector/bmdblncegkenkacieihfhpjfppoconhi)
