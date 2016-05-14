# Crash At My Pad
[![Stories in Ready](https://badge.waffle.io/adamhundley/the_pivot.svg?label=ready&title=Ready)](http://waffle.io/adamhundley/the_pivot)
[![Code Climate](https://codeclimate.com/github/adamhundley/the_pivot/badges/gpa.svg)](https://codeclimate.com/github/adamhundley/the_pivot)

<img width="1263" alt="search" src="https://cloud.githubusercontent.com/assets/8459012/15270515/ccce3a58-19df-11e6-897b-2a4f505c3c8d.png">
<img width="1276" alt="c_a_m_p" src="https://cloud.githubusercontent.com/assets/8459012/15270516/cf2bab14-19df-11e6-9682-54b3bc942e0d.png">

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
![pivot-team](https://cloud.githubusercontent.com/assets/8459012/15270392/e55f6942-19db-11e6-832e-b972c65205aa.png)
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Adam](https://github.com/adamhundley)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Alex](https://github.com/Salvi6God)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[Nate](https://github.com/natevenn)



