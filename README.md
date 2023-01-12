# RubyonRails-Movieupload-Assignment

RubyonRails-Movieupload-Assignment-API
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
