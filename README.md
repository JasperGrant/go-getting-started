# Minimal Heroku Hosted Go CRUD API Backend

Used https://github.com/heroku/go-getting-started as a template

# Code Explanation

CRUD stands for Create, Read, Update, Delete.

A Basic CRUD API should be able to do all these things through HTTP requests.

Normally you would properly connect some sort of DB but for the purpose of a hackathon this should be all right as we are not worried about long term data storage.

# File writeup

## main.go

Go code goes here

## Procfile

Sets commands to start binary compile by makefile.

## Makefile

Builds binary of main.go. Make sure that names in Procfile and Makefile match.

## heroku.yml

Sets language and name of binary

## go.mod

Documents modules used in main.go

## go.sum

Provides version numbers and more for modules in go.mod

## Dockerfile

Sets up, executes and deploys buildpack

## .gitignore

Specifies files to ignore in git

## .gitattributes

Sets attributes to pathnames

## .env

Sets environment variables