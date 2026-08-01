4.0.20

- Changed import code for Movies and TV Shows classes. Not using `manual_function_import` anymore.
- Removed True froom `listitem = self.make_listitem(True)`. Better to not use that.
- Kept session enacting until it's needed in tmdb_api.
- Switched trakt_api to use session rather than requests.

4.0.21
- Added new method to determine widget status and hopefully prevent home crashes when reuse invoker is True
- New show_text code to remove 2+ second pause before large text blocks are shown. Moved from textbox to listitems.

4.0.22
- Added a check for free space before starting download. Help needed from AI to get correct calls per OS. Cannot test across OS's though.
- Bugs in code that assigns cache expiry for movies and tv shows fixed, and those functions re-written to better reflect the current state of the media being cached.

4.0.23/24
- Goodbye the rest of Trakt!
- Re-wrote download class.

4.0.25
- Removed support for Real Debrid. So long old friend.
