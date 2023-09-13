---
{"dg-publish":true,"permalink":"/atlas/notes/x/learning-to-code/"}
---

There have been tasks and ideas that have come up now and then throughout my career where it was considered but never made into a proof-of-concept or implemented. Here I will list them out as a nice to-do list of coding project ideas for when I am just in need of technical practice.
# Specific implementations
## [[+/python scripts\|python scripts]]
- [ ] use script to access a database (postgresql)
- [ ] script to back up local folder to remote server
	- [ ] copy files to EC2
	- [ ] copy files to s3
	- [ ] tarsnap
- [ ] find SSL expiry date using python
	- [ ] when does google.com's SSL cert expire?
- [ ] develop a REST API in Flask
	- [ ] The API should include endpoints that allow users to get information on all of the books it has stored, a subset of these books and a single book
	- [ ] containerize your application as if you were deploying it to a Kubernetes cluster
## [[flask\|flask]]
- [ ] what is Flask?
	- [ ] web server
	- [ ] abstraction
- [ ] let's you query the postgres db
- [ ] is served to a browser and has buttons that trigger python code API calls
- [ ] realpython.com/flask-connexion-rest-api

## [[boto3\|boto3]]
- [ ] setup credentials
- [ ] upload a file to s3
- [ ] upload a file to an encrypted s3 bucket
- [ ] spin up an EC2 instance
- [ ] modify an EC2 instance to different instance type
	- [ ] look at terraform registry to see all the things that can be changed
- [ ] spin up 2 EC2 instances and ensure they have the same Tag, using parameterization instead of hard-coding
- [ ] managing secrets for postgres db credentials
- [ ] save credentials for local postgres in AWS secrets manager
- [ ] use boto3 to query postgres credentials

## [[postgres\|postgres]]
- [ ] timescale sharding 
- [ ] graphana dashboards
- [ ] collectd data from server
- [ ] pgBackrest

## [[+/Elixir\|Elixir]]
- [ ] DockYard Academy [[+/Elixir\|Elixir]]

## [[+/docker\|docker]]
- [ ] create an image
- [ ] create postgres in container
- [ ] create records using python
- [ ] use aws secrets manager with this image

## [[+/terraform\|terraform]]
- [ ] create a new secret in AWS secrets manager

# general coding concepts
- [ ] learn what a wrapper is
	- [ ] a kind of abstraction!
- [ ] create a wrapper for something
- [ ] create an API for something
- [ ] how to design an API
	- [ ] what do I need to know?
- [ ] leaky abstraction?
- [ ] server-side rendered web app vs client-side rendered javascript
- [ ] wttr.in
	- [ ] how is it built?
	- [ ] why is it displaying using curl