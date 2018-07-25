### Welcome to GitHub Pages.
This automatic page generator is the easiest way to create beautiful pages for all of your projects. Author your page content here using GitHub Flavored Markdown, select a template crafted by a designer, and publish. After your page is generated, you can check out the new branch:

```
$ cd your_repo_root/repo_name
$ git fetch origin
$ git checkout gh-pages
```

If you're using the GitHub for Mac, simply sync your repository and you'll see the new branch.

### Designer Templates
We've crafted some handsome templates for you to use. Go ahead and continue to layouts to browse through them. You can easily go back to edit your page before publishing. After publishing your page, you can revisit the page generator and switch to another theme. Your Page content will be preserved if it remained markdown format.

### Rather Drive Stick?
If you prefer to not use the automatic generator, push a branch named `gh-pages` to your repository to create a page manually. In addition to supporting regular HTML content, GitHub Pages support Jekyll, a simple, blog aware static site generator written by our own Tom Preston-Werner. Jekyll makes it easy to create site-wide headers and footers without having to copy them across every page. It also offers intelligent blog support and other advanced templating features.

### Authors and Contributors
You can @mention a GitHub username to generate a link to their profile. The resulting `<a>` element will link to the contributor's GitHub Profile. For example: In 2007, Chris Wanstrath (@defunkt), PJ Hyett (@pjhyett), and Tom Preston-Werner (@mojombo) founded GitHub.

### Support or Contact
Having trouble with Pages? Check out the documentation at http://help.github.com/pages or contact support@github.com and we’ll help you sort it out.


###Httplib2
A comprehensive HTTP client library that supports many features left out of other HTTP libraries.

###Requirements
Requires Python 2.3 or later. Version 0.5.0 and later includes Python 3 support.

###Documentation
There is New Python library style documentation and more detailed Examples and ExamplesPython3 for how to use httplib2 in specific situations.

There are also two articles about httplib2 on XML.com, Doing HTTP Caching Right: Introducing httplib2 and httplib2: HTTP Persistence and Authentication.

##Download/Installation
Httplib2 is a standard distutils package. See the downloading and installation instructions.

##Features
HTTP and HTTPS

HTTPS support is only available if the socket module was compiled with SSL support.
##Keep-Alive

Supports HTTP 1.1 Keep-Alive, keeping the socket open and performing multiple requests over the same connection if possible.
Authentication

The following types of HTTP Authentication are supported. These can be used over both HTTP and HTTPS.
 * Digest
 * Basic
 * WSSE
 * HMAC Digest
 * Google Account Authentication
 * Caching

The module can optionally operate with a private cache that understands the Cache-Control: header and uses both the ETag and Last-Modified cache validators.
All Methods

The module can handle any HTTP request method, not just GET and POST.
##Redirects

Automatically follows 3XX redirects on GETs.
##Compression

Handles both 'deflate' and 'gzip' types of compression.
##Lost update support

Automatically adds back ETags into PUT requests to resources we have already cached. This implements Section 3.2 of Detecting the Lost Update Problem Using Unreserved Checkout.

##Unit Tested

A large and growing set of unit tests.
Project Goal
To become a worthy addition to the standard Python library.

##Contributing
Please submit patches for review using http://codereview.appspot.com, and make sure to include httplib2-dev@googlegroups.com on the CC list. More details on the Contributor wiki page.

Contributors
Thomas Broyer (t.broyer@ltgt.net)
James Antill
Xavier Verges Farrero
Jonathan Feinberg
Blair Zajac
Sam Ruby
Louis Nyffenegger
Corey Goldberg
Mark Pilgrim
(Your Name Here)


