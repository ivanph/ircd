# ircd.js

In 2009 Ryan Dahl gave one of the first public demos of Node.js at JSConf 2009. The demo showed a simple but functional irc server.

A lot has changed since that demo and the Node API doesn't look like it did over 10 years ago. The goal here is to modernize the code to make it run in a recent version of Node and also take advantage of modern JavaScript.

# Running
If you have `node` in your path you can just run the ircd file.

        $ ./ircd.js

Or execute the file directly with npm.

        $ npm start

# TODO

- [x] Replace obsolete modules.
- [x] Replace obsolete functions.
- [x] Restore functionality.
- [ ] Move classes to separate files.
- [ ] Use `class` instead of `function` for classes (maybe).
- [ ] Use modern JS features.
