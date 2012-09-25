Contributing documentation
==========================

For documentation, we encourage contributions to Zotonic from the
community even more!


We use git for documentation. For large documentation changed, you
should take the same approach as with :doc:`contributing`: e.g. create
a fork of Zotonic, create a topic branch, make the changes, push, pull
request.

However, for small changes, typo's, et cetera, Github provides a nice
edit button which you can use to edit these ``.rst`` files.



==================
For non-developers
==================
If you want to work on the documentation, 
Download the Git-client from http://www.github.com
Go to the Masterbranch in Github.com and click on "Clone in Windows" or download the zipfile.

In Git for Windows, you can ''publish'' (push) you changes for a pull request.
To get the current Master branch, you need to open the Commandline and use the following:

``
git remote add upstream https://github.com/zotonic/zotonic.git # Assigns the original repo to a remote called "upstream"
git fetch upstream # Pulls in changes from the original repo not present in your local repository, without modifying your files. Allows you to review first.
git merge upstream/master # merge fetched changes into your working files.``


Mark-up:
one asterisk: *text* for emphasis (italics),
two asterisks: **text** for strong emphasis (boldface), and
backquotes: ``text`` for code samples.

More info on restructured text http://sphinx.pocoo.org/rest.html


`Edit <https://github.com/zotonic/zotonic/edit/master/doc/dev/documentation.rst>`_
