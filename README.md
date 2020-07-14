# snapshotalyzer-30000
Demo project to manage AWS EC2 instance snapshots


## About

This project is a demo, and uses boto3 to manage AWS EC2 instance snapshots

##configuration

shotty uses the configuration file created by the AWS CLI e.g.

`aws configure --profile shotty`

##Running

`pipenv run "python shotty/shotty.py <command> <--proect=PROJECT>"`

*command* is list, stop or start
*project* is optional
