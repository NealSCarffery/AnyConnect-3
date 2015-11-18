[![Build Status](https://travis-ci.org/raelcun/AnyConnect.svg?branch=master)](https://travis-ci.org/raelcun/AnyConnect)
[![Coverage Status](https://coveralls.io/repos/raelcun/AnyConnect/badge.svg?branch=master&service=github)](https://coveralls.io/github/raelcun/AnyConnect?branch=master)
[![Dependency Status](https://david-dm.org/raelcun/anyconnect.svg)](https://david-dm.org/raelcun/anyconnect)
[![DevDependency Status](https://david-dm.org/raelcun/anyconnect/dev-status.svg)](https://david-dm.org/raelcun/anyconnect#info=devDependencies)

# AnyConnect

A basic job scheduling service that maintains user credentials, jobs for those users, the data required for those jobs to run, as well as running the jobs on a specified schedule.

The framework is plugin based, built to allow javascript plugins to be plugged into the server without requiring a restart. The plugin framework gives complete control to the developer without requiring a lot of boilerplate code.

## Building and Testing

[Gulp](https://github.com/gulpjs/gulp) is an alternative to the popular Grunt build system that is focused on streams. The following commands can be used to control gulp:

**Build the Project**

```shell
gulp coffee
```

**Build and Watch the Project Directory for Changes**
```shell
gulp
```

**Run Tests, Outputting to the Command Line**
```shell
gulp test:console
```

**Run Tests, Outputting to HTML**
```shell
gulp test:html
```

# Special Thanks

This open source project was spawned from a project developed in collaboration with [Martin and Associates](http://martinandassoc.com/).