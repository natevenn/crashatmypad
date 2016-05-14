# Crash At My Pad
[![Stories in Ready](https://badge.waffle.io/adamhundley/the_pivot.svg?label=ready&title=Ready)](http://waffle.io/adamhundley/the_pivot)
[![Code Climate](https://codeclimate.com/github/adamhundley/the_pivot/badges/gpa.svg)](https://codeclimate.com/github/adamhundley/the_pivot)

Crash At My Pad (CAMP) is an eCommerce Rails application that was built upon [Little Owl](https://github.com/weilandia/little_owl). The main goal for this project was to learn how to "pivot" an existing business model into something completely different to reflect an agile approach of a real world scenario.

### Learning Goals
- Working with Multi-tenancy
- Implementing JavaScript
- Securing a Rails App
- Sending Email
- Creating Seed files

Production is hosted [here](http://crashatmypad.herokuapp.com/).

### Testing
All testing in Crashatmypad was done via [RSpec-rails](https://github.com/rspec/rspec-rails).  We used [shoulda matchers](https://github.com/thoughtbot/shoulda-matchers) to test database validations and relationships.  Our coverage was tested using [simplecov](https://github.com/colszowka/simplecov).
##### Running tests
Once you have the repo cloned, make sure to reset the database on your local machine and bundle.

In order to run the tests, enter `rspec` in the command line.

If you would like to run a specific test enter, the whole path of that test, preceeded by the rspec command: ie. 

```
rspec spec/features/user/user_can_search_properties_spec.rb
```

In order to see coverage for our testing suite simply type the command `open coverage/index.html` and it will show the index page for our simple cov code coverage.

###Team
![team](app/assets/images/team.png)


## Before Pivot

##### Admin Workflow


##### User Workflow

