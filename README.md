## Requirements
You must have Node.Js, aws-cdk, and python3.6+ installed on your local workstation in order to bootstrap the master-pipeline into an AWS account, see these instructions: 

[Getting Started with CDK](https://docs.aws.amazon.com/cdk/latest/guide/getting_started.html)

Inital deployment requires a role that can create a large number of resources, it maybe easiest to use an administrator role token to initially deploy this application. 

## Setup 
The initialization
process creates a virtualenv within this project, stored under the .env
directory.  To create the virtualenv it assumes that there is a `python3`
(or `python` for Windows) executable in your path with access to the `venv`
package. If for any reason the automatic creation of the virtualenv fails,
you can create the virtualenv manually.

To manually create a virtualenv on MacOS and Linux:

```
$ python3 -m venv .env
```

After the init process completes and the virtualenv is created, you can use the following
step to activate your virtualenv.

```
$ source .env/bin/activate
```

Once the virtualenv is activated, you can install the required dependencies.

```
$ pip install -r requirements.txt
```