# widerthancolumn.css: Break out of columns.

Let a section break out of the width restriction of a column.

Try the <a href="http://www.woollymittens.nl/default.php?url=useful-widerthancolumn">demo</a>.

## How to include the script

The stylesheet is best included in the header of the document.

```html
<link rel="stylesheet" href="css/widerthancolumn.css"/>
```

This include can be added to the header or placed inline before the script is invoked.

## How to start the script

```html
<aside class="wider-than-column">
```

**class : {className}** - The element to apply the effect to.

## How to build the script

This project uses node.js from http://nodejs.org/

This project uses gulp.js from http://gulpjs.com/

The following commands are available for development:
+ `npm install` - Installs the prerequisites.
+ `gulp import` - Re-imports libraries from supporting projects to `./src/libs/` if available under the same folder tree.
+ `gulp dev` - Builds the project for development purposes.
+ `gulp dist` - Builds the project for deployment purposes.
+ `gulp watch` - Continuously recompiles updated files during development sessions.
+ `gulp serve` - Serves the project on a temporary web server at http://localhost:8500/.
+ `gulp php` - Serves the project on a temporary php server at http://localhost:8500/.

## License

This work is licensed under a [MIT License](https://opensource.org/licenses/MIT). The latest version of this and other scripts by the same author can be found on [Github](https://github.com/WoollyMittens) and at [WoollyMittens.nl](https://www.woollymittens.nl/).
