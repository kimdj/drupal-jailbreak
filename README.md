# Drupal Jailbreak
Copyright &copy; 2017 Bart Massey

Drupal Jailbreak is a database scraper for
[Drupal](http://drupal.org) sites. It digs the content out
of a site by scraping the database and deposits it in
well-formatted static files, ready for deployment elsewhere.

Drupal breaks all the time. I used it as my blog site for
many years (Drupal 4 through Drupal 7), but eventually it
got to the point where it would neither run nor upgrade.
This software is my solution for getting my old blog content
back.

Drupal Jailbreak is written in Python 3 and currently
targeted at Drupal 7 Postgres content.

This is a work in progress. Its current functionality is
nonexistent, and its design is still in flux.

Useful links:
[Drupal 7 DB doc](http://www.drupal.org/node/1785994#d7),
[Drupal 7 DB content storage](http://drupal.stackexchange.com/a/6791),
[MySQLdb doc](http://mysqlclient.readthedocs.io),
[ATOM RFC](http://tools.ietf.org/html/rfc4287).

Done:

* Extract title, body and type of blog nodes
* Store in blog nodes in files named by node id

To Do:

* Give the nodes a filetype-based extension
* Filter internal reference URLs in some sane way
* Deal with (B) and other smileys
* Get static pages out as well as blog nodes
* Figure out how image attachment works and rescue images
* Extract comments and attach them somehow

This work is made available under the MIT license. Please
see the file `COPYING` in this distribution for license terms.
