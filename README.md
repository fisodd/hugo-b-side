# Hugo B-side

A theme for [Hugo](https://gohugo.io/)
using
[reStructuredText](http://docutils.sourceforge.net/rst.html)
markup to produce clean column-and-sidenotes article postings

See the
[live demo](https://hugo-b-side-demo.netlify.com/).

Features

- Responsive 2-column page layout (scales from 300 to 1300 pixels wide)
- Supports reStructuredText markup features

Including

- [Images](https://hugo-b-side-demo.netlify.com/post/using-bside/#images) and [figures](https://hugo-b-side-demo.netlify.com/post/tufte/#figures)
- [Sidenotes](https://hugo-b-side-demo.netlify.com/post/tufte/#sidenotes) and [citations](https://hugo-b-side-demo.netlify.com/post/hugo-and-rest/#citations)
- [Pull-quotes](https://hugo-b-side-demo.netlify.com/post/hugo-and-rest/#pullquotes) and [epigraphs](https://hugo-b-side-demo.netlify.com/post/tufte/#epigraphs)
- [Sidebars](https://hugo-b-side-demo.netlify.com/post/using-bside/#sidebars)
- [Admonitions](https://hugo-b-side-demo.netlify.com/post/using-bside/#admonitions) and topics, notably including topics containing the [table of contents](https://hugo-b-side-demo.netlify.com/post/using-bside/#contents)
- Support for [inline math](https://hugo-b-side-demo.netlify.com/post/using-bside/#math) and [code directives](https://hugo-b-side-demo.netlify.com/post/tufte/#code)
- [Tables](https://hugo-b-side-demo.netlify.com/post/using-bside/#tables), including all forms of reStructuredText alternative table markup: [list-tables](http://docutils.sourceforge.net/docs/ref/rst/directives.html#list-table), [field lists](http://docutils.sourceforge.net/docs/ref/rst/restructuredtext.html#field-lists), even [bibliographic fields](http://docutils.sourceforge.net/docs/ref/rst/restructuredtext.html#bibliographic-fields)

With

- The ability to place any of these elements in a sidebar
that runs the length of the page.

All of these features and some more are demonstrated in
[the live demo](https://hugo-b-side-demo.netlify.com/).

![Screenshot](https://github.com/fisodd/hugo-b-side/raw/master/images/tn.png)


## Installation

Installation is much like any other Hugo theme.

Use of the reStructuredText features will require the installation
of Docutils (and Pygments for code highlighting), but Hugo automatically
recognizes ReST files and will call these packages if installed.


### Getting started

Inside the folder of your Hugo site run:

    $ cd themes
    $ git clone https://github.com/fisodd/hugo-b-side.git

For more information read
[install and use themes](https://gohugo.io/themes/installing-and-using-themes/)
or begin with Hugo's
[get started](//gohugo.io/overview/installing/) help page.


### The config file

Inside the
[`exampleSite`](https://github.com/fisodd/hugo-b-side/tree/master/exampleSite)
folder of this theme, there is a file called
[`config.toml`](https://github.com/fisodd/hugo-b-side/blob/master/exampleSite/config.toml).
Use this configuration as an example,
and modify to suit your needs.


### Create your content as ReST files

Create a piece of content with ".rst" as the suffix.

example:

    $ hugo new content/post/first-post.rst

Note: Hugo recognizes files ending with a ".rst" suffix as
[reStructuredText](http://docutils.sourceforge.net/rst.html)
and will call out to the [docutils](http://docutils.sourceforge.net/)
python package to process these files.


### See the results

In order to see your site in action, run Hugo's built-in local server.

    $ hugo server

Now enter [localhost:1313](localhost:1313)
in the address bar of your browser.


## License

This theme is released under the MIT License.

The specifics can be found within the [License](/LICENSE)


## Recognition

The layout and style of this theme was inspired by
[Tufte CSS](https://edwardtufte.github.io/tufte-css/)
and the other projects following the ideas of Edward Tufte.

The author learned most of what he has learned about Hugo themes
by studying the excellent example of the
[Ananke theme](https://github.com/budparr/gohugo-theme-ananke).
I am very grateful for the clean implementation and the helpful comments.

Also, many, many thanks to
[all the folks](https://github.com/gohugoio/hugo/graphs/contributors)
who make Hugo rock.

