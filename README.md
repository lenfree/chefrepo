Chefrepo
===========
Description: 

A Chef repo for my recipes.

Project Setup:
=================

$ curl -L https://www.getchef.com/chef/install.sh | sudo bash
$ bundle install --path=.gems --binstubs=.bin 

How do I run the project's automated tests?
===========================================
Unit Tests

rake spec
Integration Tests

Run other local services / provide credentials for external services.
rake spec:integration

Deploying:
============

How to setup the deployment environment

Required heroku addons, packages, or chef recipes.
Required environment variables or credentials not included in git.
Monitoring services and logging.
How to deploy

