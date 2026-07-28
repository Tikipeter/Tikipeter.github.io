4.0.20

- Changed import code for Movies and TV Shows classes. Not using `manual_function_import` anymore.
- Removed True froom `listitem = self.make_listitem(True)`. Better to not use that.
- Kept session enacting until it's needed in tmdb_api.
- Switched trakt_api to use session rather than requests.

4.0.21
- Added new method to determine widget status and hopefully prevent home crashes when reuse invoker is True
- New show_text code to remove 2+ second pause before large text blocks are shown. Moved from textbox to listitems.
