# HelloWorldExampleApp

HelloWorldExampleApp is a Lift app that used the [HelloWorld Lift Module](https://github.com/pr1001/HelloWorld). HelloWorld is a Lift module (the first in fact) which illustrates how you can package useful code so that it can be easily reused in any [Lift](http://www.liftweb.net) project. This app simply imports the HelloWorld module, which adds a Hello World page to its SiteMap.

## Using this app

This app uses Scala 2.81 and Lift 2.3-SNAPSHOT. You can run it by checking out this project, building it using sbt, and then running the jetty target. For example you might do something like this:

    $ sbt
    > update
    ...
    > jetty

If you get errors with the update task, it may be because I am currently (2011-01-08) having problems with my web server which mosts the HelloWorld jar. Despite such errors, you should still be able to successfully run the app with the jetty task.

## Authors

This HelloWorldExample App and the HelloWorld module were written by [Peter Robinett](http://www.bubblefoundry.com). The Lift Module conventions were developed by the [Lift community](http://groups.google.com/group/liftweb/), including Richard, George, and David.
