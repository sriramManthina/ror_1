# README

## commit - initial setup
    * terminal commands: 
        * create new rails app: rails new app_name
        * run rails app: go to that directory and type "rails s"
        * fetch all current routes: rails routes --expanded

## commit - added pages controller
    * general: added a pages controller
    * terminal commands:
        * create a new controller: rails generate controller pages

## commit - added about route
    * general: added /about route

## commit - created a resource 'Article'
    * general: crud operations on /articles using scaffold generator
    * terminal commands:
        * create a new resource: rails generate scaffold Article title:string description:text
        * migragte the db: rails db:migrate