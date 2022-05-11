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


Ruby 3.1.2p20
Rails v 7.0.3


* Features to be aware of and patched on Windows install:
Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: %i[ mingw mswin x64_mingw jruby ]
gem "tzinfo-data"

Hotwire destroy not working out of the box:
Rails 7: link_to method: :delete not working #44185
$ rails importmap:install $ rails turbo:install stimulus:install
