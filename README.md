# snapshotalyzer-30000
Demo project to manage AWS EC2 instance snapshots


## About

This project is a demo, and uses boto3 to manage AWS EC2 instance snapshots

##configuration

shotty uses the configuration file created by the AWS CLI e.g.

`aws configure --profile shotty`

##Running

`pipenv run "python shotty/shotty.py <command><subcommand> <--proect=PROJECT>"`

*command* is instances, volumes or snapshots
*subcommand* depends on command
*project* is optional
