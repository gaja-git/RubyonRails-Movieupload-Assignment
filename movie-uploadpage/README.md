# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

- Ruby version

- System dependencies

- Configuration

- Database creation

- Database initialization

- How to run the test suite

- Services (job queues, cache servers, search engines, etc.)

- Deployment instructions

- ...
  Create new project:
  rails new movie-uploadpage

Execute rails :
rails s

Create new controller:
rails generate controller pages

in config/route.rb

root "pages#home"

in app/controllers/pages
pagecontroller.rb

in app/views/pages create
home.html.erb

create movie
rails generate scaffold Movie Name:string Description:string Director:string Language:string
db:migrate
