This is a sample application that showcases the [Parse JavaScript SDK](https://www.parse.com/docs/js_guide). It's based on the [canonical Backbone Todo app](http://addyosmani.github.com/todomvc/).

[View the live application hosted on Parse here](http://todolist.parseapp.com).

[Learn how we built it in the tutorial](https://parse.com/tutorials/todo-app-with-javascript).

Compiling Templates
[Handlebars](http://handlebarsjs.com/) is used for templating

To install, you'll need Node.js and npm

On Fedora:
```yum install nodejs npm```

Then:
```npm install -g handlebars```

Then to compile:
```handlebars handlebars/* -m > js/tmpl.js```
