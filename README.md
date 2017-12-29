# Meteor Todo List with CaptainDuckDuck


To run:

1. Create a MongoDB instance on your CaptainDuckDuck instance using one-click app and name it `meteor-test-db`

2. Create a regular webapp in CaptainDuckDuck, name it `meteortest` and set the following env variables:
- `ROOT_URL` `http://meteortest.captainrootdomain.domain.com`
- `MONGO_URL` `mongodb://<USERNAME>:<PASSWORD>@srv-captain--meteor-test-db:27018/test-meteor`

3. On you local machine run:

```
git clone https://github.com/githubsaturn/meteor-captainduckduck.git

cd meteor-captainduckduck

captainduckduck deploy

```

--------------


# IMPORTANT NOTES:

Build process for Meteor apps is ridiculously heavy. It requires at least 2 CPU cores and 4GB of RAM. And it still can take up to 4 minutes to complete. So you might see a timeout error when deploying the app.


# Forked from:
https://github.com/meteor/simple-todos


The Meteor Tutorial app.

Use it to share a single todo list with your friends. The list updates on everyone's screen in real time, and you can make tasks private if you don't want others to see them.

Learn how to build this app by following the [Meteor Tutorial](http://www.meteor.com/install).

Read more about building apps with Meteor in the [Meteor Guide](http://guide.meteor.com).

![screenshot](screenshot.png)