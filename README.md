## Starter Code for Building Web Applications with hapi

This repository contains the starter code for the [Building Web Applications with hapi course on Pluralsight.com](http://www.pluralsight.com/courses/hapi-building-web-applications).

##Course Note
Please use hapi version 8.x for this course. There are some breaking changes in version 9 that will make pieces of the course demo not work. Some examples of this are the need to include [inert](http://www.github.com/hapijs/inert) and [vision](https://github.com/hapijs/vision) for returning static files or views.

To install a version of hapi that works for this course, use the following syntax when installing:
```sh
npm install hapi@v8.8.1 --save
```

Also, the ```hapi-auth-cookie``` package also has some newer breaking changes. Install the specific used in this course with this command:
```sh
npm install hapi-auth-cookie@2.2.0 --save
```
