# ChessDatabase
A curated database of chess games. 

Work done to maintain database integrity includes:
* Spell-checking player, event, site and round names
* Deleting twin games
* Removing games after 1971 with a no rating, or a rating of 1800 or less
* Removing games that had PGN parsing errors
* Removing Chess960 games, as SCID's file format doesn't support this variant without a software patch
---
A big thanks to the developers of [SCID](http://scid.sourceforge.net/) and [SCID vs PC](http://scidvspc.sourceforge.net/), as these provided the basis for cleaning and maintaining the data.
