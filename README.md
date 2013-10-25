# Decent Authentication
[![Build Status](https://secure.travis-ci.org/leesmith/decent_authentication.png?branch=master)](http://travis-ci.org/leesmith/decent_authentication) [![Code Climate](https://codeclimate.com/github/leesmith/decent_authentication.png)](https://codeclimate.com/github/leesmith/decent_authentication)

Decent Authentication is a sample application that implements authentication in Rails 3.2 without the use of a third-party generator or engine.  This is essentially a complete reproduction of [Ryan Bates' Authentication from Scratch railscast](http://railscasts.com/episodes/250-authentication-from-scratch-revised) with my addition of RSpec unit and integration tests. In addition to authentication, features include rememberable cookie, password reset, and forwarding to protected routes.

See the 'rails-3.0' tag for a legacy Rails 3.0 implementation.

## Dependencies

* Ruby 1.9+

## Getting Started

```
# install gems, create database.yml config, and setup the database
./bin/setup

# run the test suite
./bin/rake
```
