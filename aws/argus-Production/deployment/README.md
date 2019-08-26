# Argus-Production

One Paragraph of project description goes here

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See below documentation on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

```
Install Python 3.5 or greater
Install Sceptre
Install AWS Cli	
```

### Installing

A step by step series of examples that tell you how to get a environment running.

Directory structure should be as shown below.
```
argus-production.
└───deployment
    ├───config
    │   ├───dev
    │   ├───prod
    │   ├───stage
    │   └───test
    └───templates
```
To install Sceptre we need to have PIP, Which would be available after installing Python(3.5 or later).

```
	pip install sceptre==1.4.2
```
Install AWS CLI for configuring Secrect Keys.

```
	pip install awscli
```

## Deployment

Below are the examples on how to deploy the Complete Environment or individual stack.

Run a complete Environment.

```
syntax : Scepter --dir deployment lauch-env <environment_name> 
```

```
Example : 	Scepter --dir deployment lauch-env prod

```

Run an individual Stack

```
syntax : Scepter --dir deployment lauch-env <environment_name> 
```

```
Example : Scepter --dir deployment lauch-env prod workspace
```


## Built With

Cloudformation Scripts to automate the Deployment of the Environment.
Tamplates are created using Json and Config files are for each stack are in yaml.

## Versioning
1.0.0


