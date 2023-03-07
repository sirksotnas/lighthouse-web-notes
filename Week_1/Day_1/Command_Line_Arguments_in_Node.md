### What are Command Line Arguments?

* are strings of text used to set configuration or property values for when an application run through [command line interface](https://en.wikipedia.org/wiki/Command-line_interface) (CLI) of an operating system.

* Example:
```
$[runtime] [script_name] [argument-1 argument-2 argument-3 ... argument-n]
```

* runtime is a program/script that executes a program, separated by a space and can pass arguments in key-value pairs.

### Why Use Command Line Arguements?

### Advantages:

* Passing information to an application before it starts is useful for large-scale configuration settings.

* String arguments can be easily converted to other data types, making them flexible.

* Command line allows for unlimited arguments to be passed.

* Command line arguments are used in conjunction with scripts and batch files, which is particularly useful for automated testing.

### Disadvantage

* The command line interface has a steep learning curve, making it difficult for most people to use.

* Command line applications are difficult to use on smaller devices.

### Passing Command Line Arguments in Node.js

* Node.js applications can accept command line arguments, with third-party packages providing useful features.

### Using process.argv

* The simplest way to retrieve arguments in Node.js is via the process.argv array.

* The first element of the process is a file system path, the second element is the name of the JavaScript file, and the third element is the first argument passed by the user.

Example: [progressargv.js](/focal/processargv.js)

