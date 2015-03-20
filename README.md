Pinned
===================

Project
-------------------
Build a [Pinterest](https://www.pinterest.com/) style application, with users and pins.

Utilized the following project specific gems:
- `gem 'haml'`
  - [Haml](https://github.com/haml/haml) is a templating engine for HTML.
- `gem 'simple_form'`
  - [Simple Form](https://github.com/plataformatec/simple_form) is Rails forms made easy, used for pins.
- `gem 'bootstrap-sass'`
  - [Bootstrap-Sass](https://github.com/twbs/bootstrap-sass) is a Sass-powered version of Bootstrap, ready to drop right into your Sass powered applications.
- `gem 'paperclip'`
  - [Paperclip](https://github.com/thoughtbot/paperclip) is intended as an easy file attachment library for Active Record, used here for pin images.
- `gem 'devise'`
  - [Devise](https://github.com/plataformatec/devise) is a flexible authentication solution for Rails based on Warden.
- `gem 'masonry-rails'`
  - [Masonry](https://github.com/kristianmandrup/masonry-rails) is a dynamic grid layout plugin for jQuery, used here for pin transitions.
- `gem 'acts_as_votable'`
  - [Acts As Votable](https://github.com/ryanto/acts_as_votable) is a Ruby Gem specifically written for Rails/ActiveRecord models allowing for model to be voted on, like/dislike, upvote/downvote, etc. Used here to 'heart' particular pins.

App Features
-------------------
- A user can sign up/sign in and out.
- A user can edit their account details.
- A user can submit a pin.
- A pin can include title, description and uploaded image.
- A user can like or 'heart' a pin.

