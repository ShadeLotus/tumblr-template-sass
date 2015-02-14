Please backup your existing template before using this alpha version.

#tumblr-template-sass
--------------------

Tumblr template using SASS, Compass, Gulp, and Bower.

## INSTALLATION
### Global Assets
I assume you have installed node, npm (node package manager), and gem (RubyGem -- ruby's package manager).
If not, please install each of them.

http://nodejs.org/
https://www.npmjs.com/
https://rubygems.org/

### Necessary packages
```bash
 npm install -g bower  # bower required
 gem install compass   # compass required
```

### Clone, setup, and gulp
```bash
 git clone https://github.com/shadesoflight/tumblr-template-sass
 cd tumblr-template-sass
 npm install
 bower install
 gulp
```

Gulp will end with a watch task, recompiling the templates and sass files when you edit them.
All assets are compiled into the build directory in the root of the cloned repository.

 - copy the contents of build/theme.tumblr to the theme's HTML editor
 - upload and insert both theme.js and theme.css as static assets
