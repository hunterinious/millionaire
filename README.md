# The application "Millionaire"
## Educational application

## Anotation
The project was implemented on Ruby on Rails (v4.2.6) for educational purposes.

## Short description
Game for children from 12 to 159 years.
Ruby on Rails course application from [Good Programmer](https://goodprogrammer.ru/). In production, set up to work with Heroku.

## Tested / used technologies:
- [RSpec](https://github.com/rspec/rspec-rails)
- [FactoryGirl](https://github.com/dscape/factory_girl_rails)

## Install and Run
Before running the application, you must install all the necessary gems and prepare the database. To do this, in the console in the directory with the application, you must run the following commands:

```
bundle install
bundle exec rake db: migrate
```

To start the local server, run the following command:

`bundle exec rails s`

The list of all used gems is specified in the Gemfile file.

### Demo
The latest current version of the application is running [here](https://hwbm.herokuapp.com/)
