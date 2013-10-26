study-play-scala
================

I study PlayFramework

http://www.playframework.com/ <br>
http://www.scala-lang.org/

## Install

```sh
% brew update
% brew install scala
% brew install play
```

## Hello world

### create play project.

```sh
% play new todolist

       _
 _ __ | | __ _ _  _
| '_ \| |/ _' | || |
|  __/|_|\____|\__ /
|_|            |__/

play 2.2.0 built with Scala 2.10.2 (running Java 1.7.0_45), http://www.playframework.com

The new application will be created in /Users/funnythingz/github/study-play-scala/todolist
What is the application name? [todolist]
>

Which template do you want to use for this new application?

  1             - Create a simple Scala application
  2             - Create a simple Java application

> 1
OK, application todolist is created.

Have fun!
```

### play

```sh
% play

Getting org.scala-sbt sbt 0.13.0 ...
:: retrieving :: org.scala-sbt#boot-app
	confs: [default]
	43 artifacts copied, 0 already retrieved (12440kB/95ms)
[info] Loading project definition from /Users/funnythingz/github/study-play-scala/project
[info] Set current project to todolist (in build file:/Users/funnythingz/github/study-play-scala/)
       _
 _ __ | | __ _ _  _
| '_ \| |/ _' | || |
|  __/|_|\____|\__ /
|_|            |__/

play 2.2.0 built with Scala 2.10.2 (running Java 1.7.0_45), http://www.playframework.com

> Type "help play" or "license" for more information.
> Type "exit" or use Ctrl+D to leave this console.

[todolist] $
```

### run

```sh
[todolist] $ run
[info] Updating {file:/Users/funnythingz/github/study-play-scala/}study-play-scala...
[info] Resolving org.fusesource.jansi#jansi;1.4 ...
[info] Done updating.

--- (Running the application from SBT, auto-reloading is enabled) ---

[info] play - Listening for HTTP on /0:0:0:0:0:0:0:0:9000

(Server started, use Ctrl+D to stop and go back to the console...)

[info] Compiling 5 Scala sources and 1 Java source to /Users/funnythingz/github/study-play-scala/target/scala-2.10/classes...
[info] play - Application started (Dev)
```

## Setting up IntelliJ

http://www.jetbrains.com/idea/

```sh
[todolist] $ idea with-sources=yes
```
