# Server Cheatsheet
## Background
As a student in General Assembly's Web Development Immersive Program, we learn many technologies, making it sometimes difficult to remember all the terminal commands to start up my local server. So I'm making a cheatsheet for myself. 

Feel free to open a PR to add to this list. The more, the merrier.

## Rails
```
$ rails s
```
or
```
$ rails start
```
note: start with a ```bundle install```

## Sinatra
```
$ ruby [filename.rb]
```
note: must have Sinatra required in file. For example: ``` require 'sinatra' ```
Port defaults to :4567

## Reactjs
```
$ npm start
```

## Node
```
$ node [filename.js]
```
note: create json package ```npm init -y```

### Using nodemon
```
$ nodemon [filename.js]
```
note: index.js is the default file, do not need to specify filename if using default

## Angular
```
$ hs
```
or to define port number:
```
$ hs -p [port number]
```
note: Url must have hashtag /#/appname in order to run on local

## MongoDB
```
$ mongod
```
for finicky machines (not recommended)
```
$ sudo mongod
```
MongoDB shell version, for querying database
```
$ mongo
```
note: helpful commands include ``` $ show dbs ``` and ``` $ use [databaseName] ```

## Jekyll

```
$ bundle exec jekyll serve
```
