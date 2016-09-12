
# grunt-bucklescript

JavaScripts your bucklescript

## Getting Started
Install this grunt plugin next to your project's [grunt.js gruntfile][getting_started] with: `npm install grunt-bucklescript`

Then add this line to your project's `grunt.js` gruntfile:

```javascript
grunt.loadNpmTasks('grunt-bucklescript');
```

[grunt]: https://github.com/askucher/grunt-bucklescript


## Documentation
You'll need to install `grunt-bucklescript` first:

    npm install grunt-bucklescript

Then modify your `grunt.js` file by adding the following line:

    grunt.loadNpmTasks('grunt-bucklescript');

Then add some configuration for the plugin like so:

    grunt.initConfig({
        ...
        bucklescript: {
          app: {
            src: ['path/to/bucklescript/files/*.ocaml'],
            dest: 'where/you/want/your/js/files',
            options: {
                
            }
          }
        },
        ...
    });

Then just run `grunt bucklescript` and enjoy!
