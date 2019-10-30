# snapshotalyzer-30000
Demo project to manage EC2 instances

## About

This project is a demo, and uses boto3 to manage AWS EC2 instance snapshots.

## Configuring

acg uses the configuration file created by the AWS CLI, e.g.

`aws configure --profile acg`

## Running

`pipenv run python "acg/acg.py <command> <--project=PROJECT>"`

*command* is list, start, or stop
*project* is optional