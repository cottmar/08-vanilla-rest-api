#Author 
Cara Ottmar, Version 2.0.0

#Overview
 Use promise constructs to manage asynchronous code

#Architecture
 Set up your configuration: README.md -- with a documentation about your lab gitignore -- with a robust .gitignore eslintrc -- with the class .eslintrc file eslintignore -- with the class .eslintignore package.json -- with all dependencies and dev-dependencies lib/ -- directory for holding your programs helper modules test -- directory for holding your programs unit and integration tests .env - contains env variables (should be git ignored) (http://gitignore.io) .gitignore file package.json - contains npm package config
-create an HTTP server using the native NodeJS `http` module
-create an object constructor that creates a simple resource with at least 3 properties
  -include an `id` property that is set to a unique id 
  -include two additional properties of your choice (ex: name, content, etc.)
-create a custom body parser module that uses promises to parse the JSON body of `POST` and `PUT` requests
-create a custom url parser module that returns a promise and uses the NodeJS `url` and `querystring` modules to parse the request url
-create a router constructor that handles requests to `GET`, `POST`, `PUT`, and `DELETE` requests
-create a storage module that will store resources by their schema type (ex: note) and id

# Logs
4-25-2018 -- Built structure and added dependencies needed
4-25-2018 - Added the delete function and worked on testing
5-6-2018 - added readme.

#Credits
 Josiah, Joshua, Zac, and Mike