## PYTHON UBER PROJECT
## Summary
Uber have released an example application that uses their external API. It is built in Python using flask.

The task was to create working development, testing and production environments and to build a pipeline to move the code through them using Jenkins.

### How to start
You should start by cloning this repo into a new directory;

`mkdir UberApp`

`cd UberApp`

`git clone`

`git pull origin master`

### Generate the Cookbooks
To view the cookbooks use command;

`berks vendor cookbooks`

Then spin up the virtual machine using;

`vagrant up`

To View Page
Go to http://development.local/

Or use IP address: 192.168.10.100

### Notes
If you are trying to run `kitchen test` and get a parsing error message, then type `chef gem install kitchen-ec2` into your terminal.
