### Background

This repo contains the scaffolding of a simple Rails list management application.
It's built with Rails and Backbone, much like Everlane's website.

This exercise is designed to simulate as closely as possible, the kind of work we do at Everlane.

### Description

The Lists app allows the user to view and edit nested lists of content.

Initial feature list:
- the user can view root level items
- that's it

**Implement the following feature set by extending the codebase.**

#### Features

- the user can view fully nested items
- items maintain an order defined in the data model (add a position column)
- the user can collapse the nested item views (like closing a folder in a file explorer)
- the user can edit the title and content values of each item and save the state to the database
- the user can drag and drop to reorder the items within a list
- the user can drag and drop to next an item under a different list

#### Parameters

- The application should be single-page and communicate with the server using AJAX
- You can include any open source libaries you want, with the exeption of full JavaScript frameworks like Ember and Angular.
In other words, stick with Backbone!

#### Requirements

Fork this repo in github and send us the link to your project once you are done.

- Optimize for good object-oriented design and an organized codebase
- Readibilility is very important, comments are useful to explain tricky bits of logic, but use them sparingly
- Don't worry about styling or visual asthetics

#### Getting Started

You will need to have a working Rails enviornment with sqlite. Once you have cloned the repo, run `rake db:setup`. If you run into any issues getting started, email us and we can help.

#### Notes

- Search out and eliminate bugs
- Eliminate position data attribute set and get, as not needed
- Add ability to nest an item, not just a list
- Improve graphics
- Allow addition of an item
- Use SQL or ActiveRecord to get necessary values, not enumerable methods
