# DBC Oven

This is a simple application which is designed to assess your competency with
the core concepts evaluated in the portfolio challenges.  Don't wig out, if
you've been keeping up with things you should be comfortable with this.

# Release 0:  Bootstrap an Application

* Get [sinatra_skeleton_mvc](https://github.com/sea-lions-2014/sinatra_skeleton_mvc)
* Create an `Oven`
  * lives in a restaurant (string)
  * has many Foods
  * The restaurant defaults to "Unknown restaurant"
* Create a `Food`:
  * belongs to an Oven
  * has a name (string)
  * the name cannot be blank

# Build an application and a few basic routes

* Create a route to show all the Foods
* Create a route to show an oven and all its associated food.  This should be
  a simple UI:  oven name in an <h2> and the foods in a <ul>
* Use a partial to put a header in on your route
* Use a partial to put a footer in on your route

# CRUD

* Add a route to add a food (non-ajax)
* Add a route to add an oven (non-ajax)
* Display errors if bogus data is entered


Javascript
==========

* Create a class called Garment
* It supports a method called wrinkle()
* It has an attribute called "type"
* it has a method called describe() which prints the type

Back to the Oven
================

* Select all the <li>s on the Food page, apply a red border around each of them
  with pixel width 1px
* Add an ajax handler to the <li>s.  When you click on it, send that word to a
  route, the route returns that word but wrapped in an <h2>.  When the callback
  finishes take that text (i.e. <h2>spaghetti</h2>) and append it to the
  document

