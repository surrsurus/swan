# swan
Swan - An HTML Templating Tool made in Python

# Usage

`swan.py <source dir> <template dir> <build dir>`

Swan will analyze the source directory for all insances of `{{template}}` in your .html files where `template` is some `template.html` located in the template directory. It will then move the contents of `template.html` to where `{{template}}` is. Swan will preserve directory structure and preserve any non-html files present in the source directory and copy them to the build directory.

Swan is intended to be used as a lightweight templating tool so copy things like navigation bars and footers across all of your webpages simultaneously if you aren't using a static site generator. See the example folder for more information.
