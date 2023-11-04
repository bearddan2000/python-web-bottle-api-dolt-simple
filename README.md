# python-web-bottle-api-dolt-simple

## Description
Simple web app that serves an api
for a bottle project.

Uses sqlalchemy query a table `dog`.

## Tech stack
- python
  - bottle
  - sqlalchemy
- dolthub/dolt-sql-serverdb

## Docker stack
- python:latest
- dolthub/dolt-sql-serverdb:latest

## To run
`sudo ./install.sh -u`
- [Endpoint at](http://localhost/dogs)

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
[Bottle sqlalchemy setup](https://github.com/iurisilvio/bottle-sqlalchemy/blob/master/examples/basic.py)
