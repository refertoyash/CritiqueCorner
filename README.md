## OpenFlights 
### A flight reviews app built with Ruby on Rails and React.js

This app is intended to be a simple example of a CRUD app built with **Ruby on Rails** and **React.js** using **Webpacker**.


This app uses:

* Ruby version: `2.7`
* Rails version: `6.0.3.4`
* Database: `postgresql`
* React version: `16.12.0`
* React Hooks API
* React Context API

## Running it locally
- run `bundle exec rails db:prepare`
- run `npm install` or `yarn install`
- run `bundle exec rails s`
- in another tab run `./bin/webpack-dev-server` (optional) 
- in another tab run `sidekiq` (optional, but necessary for things like password reset emails)
- navigate to `http://localhost:3000`

 
  
