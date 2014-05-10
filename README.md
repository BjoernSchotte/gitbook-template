Buchtitel
=======

This is a template for writing books with gitbook. Grundfile.js was heavily inspired by
the JavaScript book at https://github.com/GitbookIO/javascript

Pre-Requisites
=======

````
$ sudo npm install -g gitbook gitbook-pdf grunt
$ sudo npm install gitbook-plugin-disqus gitbook-plugin-richquotes grunt-gitbook grunt-gh-pages grunt-contrib-clean
$ gitbook serve
```

Notice on older gitbook versions
========

Please use at least gitbook V0.4.2 or higher. Otherwise, changed links in book.js won't work.

If you want to install gitbook in version 0.4.2, type

````
$ sudo npm install -g gitbook@0.4.2
```


Customization
========

Adapt book.json to your needs.

**Note:** shortName for disqus plugins equals to the shortname of your http://diqus.com configuration.

Please finde documentation for the richquote Plugin at https://github.com/erixtekila/gitbook-plugin-richquotes

Build the book with grunt
======

With grunt the book can be published directly to a gh-pages branch on your github repo:

````
$ grunt publish
```


License
======

This book is published by the [following license](LICENSE.md).