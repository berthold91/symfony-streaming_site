# Symfony Video Streaming Site

- i am using **Symfony/skeleton v6.0.99**
- it is very impotant to use the symfony documentation, when you are working on a symfony project (the doc is available on *https://symfony.com/documentation*)

## project step by step

#### step-1) project and environment setup:

- install XAMPPs
- open xampp and start apache and MySql
- go in the htdocs folder of XAMPP and run:
  - composer create-project symfony/skeleton yourProjectName
- your project is accessible on http://localhost/yourProjectName

#### step-2) let create our local and remote git repositories:

(we assume that you already have a github account)

- go to https://github.com, connect to your account and create a new repository (add a README file when creating)

* go to your project folder and run git init => the .git folder will be created, which is our local repository
*

#### step-3) let move our template and make all links working:

1. let's first install some important dependencies

- install annotation using composer...it will help us creating route
- install twig using composer... for templation
- install doctrine orm..and modify your DATABASE_URL config in .env
- install symfony maker using composer...for creating controllers, models ..
- commit your chages
