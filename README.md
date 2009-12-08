md2html
=======

Developed and copyrighted by
----------------------------
Jan Andersson <<jan.andersson@gmail.com>>

License
-------
Released under the [MIT license](http://www.opensource.org/licenses/mit-license.php)

Description
-----------
Command line tool for coverting [John Gruber's Markdown](http://daringfireball.net/projects/markdown/) formatted text to HTML. Also incorporates [Github Flavored Markdown](http://github.github.com/github-flavored-markdown/).

Usage
-----
    Usage: md2html [options] file1 file2 ...
        -o, --open                       Open after conversion
        -h, --help                       Display this screen

Installation
------------
* Install Ruby
* Install required gems
        sudo gem install rdiscount activesupport
* Copy md2html to directory existing in PATH
        cp md2html /usr/local/bin

TODO
----
Turn this into a gem!
