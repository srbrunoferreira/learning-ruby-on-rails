# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...


```bash
brew install postgresql
brew services start postgresql


rails g scaffold Post title:string description:text thumbnail_url:string video_url:string pro:boolean
rails db:migrate
rails s
```
