CHANGELOG
=========

0.3.1 (2015-01-18)
------------------

* updated the Changelog

0.3.0 (2014-12-13)
------------------

* Removed ParserAbstract, Parser/Rss Parser/Atom
* Added Parser class. This class parses a Feed using a Standard
* Added StandardAbstract
* Added Standard/Atom
* Added Standard/Rss
* Added Formatter class. This class formats a Feed using a Standard 

0.2.0 (2014-11-23)
------------------

* added ClientInterface to handle HTTP queries
* added ParserAbstract
* added Parser/Rss
* added Parser/atom
* Feed now extends Item

0.1.0 (2014-09-06)
------------------

* added FeedInterface to represent a Feed which is the whole RSS/Atom document
* added NodeInterface to represent a Node which contains basic attributes of the whole document or an item
* added ItemInterface to represent an Item
* project structure