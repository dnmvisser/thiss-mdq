Release Notes
=============

Version 1.1.4
-------------

* escape special characters in plain text queries

Version 1.2.0
-------------

* pluggable indexing and redis-support from Hannah Sebuliba

Version 1.2.1
-------------

* bugfixes

Version 1.2.2
-------------

* updates to the search algorithm to favor more exact searches over less

Version 1.2.3
-------------

* Integrate stopwords module instead of locally maintained stopwords

Version 1.2.4
-------------

* Enforce AND-logic for combining multiple search terms

Version 1.2.5
-------------

* Never treat the first token as a stopword

Version 1.2.6
-------------

* Reduce index memory footprint
* Use cluster controller for expressjs

Version 1.3.0
-------------

* Discontinue support for automatic restarts - rely on external restart
* Change tokenizer to split tokens on whitespace only
* Improved i18n-support
* Provide information about metadata mtime in monitor json

Version 1.3.1
-------------

* Updated and extended status json information: mtime and ctime for the metadata file is reported separately

Version 1.3.2
-------------

* Avoid including user-supplied data in header values

Version 1.3.3
-------------

* Allow filtering with trust info.
* Remove dashes and pluses from free text queries

Version 1.4.6
-------------

* Positive hints in entities selected by trust profile
* Add trust info metadata to discojson representation of SPs
* Add /tinfo endpoint to serve trust info metadata
* Updated dependencies and a couple of bug fixes
