4.0.42
- Again reworked downloader. Some AI used for code for establishing remaining storage on a user's system etc, as well as the actual download loop, which is over my head and replaces code written by someone many years ago (we should all thank spoyser).
- Added list editor dialog with built in buttons for move up/down and enable/disable. Perfect for settings like enabled and sorted extras items or context menu items.
- As a result, re-added custom context menu throughout media lists.

4.0.41
- Mainly involving fixing Fen Online related issues.

4.0.38/39/40
- Fix OC cloud scraper.
- More changes to download function.

4.0.36/37
- Rewrite of Fen Online Service.

4.0.29/30/31
- Added Personal Lists to Fen Online.
- Re tooling of Downloads Manager dialog. Now includes download speed and estimated remaining time until finished.
- Added settings for max speed and max simultaneous downloads.
- Added new queue manager to manage all downloads, not just pack downloads.
- Began switching online backup service to new name "Fen Online", and began adding other services besides watched history i.e. Personal Lists coming soon.
- Re-added Watched Indicators setting so as to choose between Fen Local or Fen Online.
- Added ability to open settings at certain menu item using 'menu_focus' and 'submenu_focus'.
- Switched Update to check all online versions available, rather than the 'fen_version' text file.

4.0.28
- Added online backup sync service for watched and progress statuses.

4.0.27
- Fixed Easynews thumbnails:

VIDEO THUMBS: `https://th.easynews.com/thumbnails-%s/pr-%s.jpg % (post_hash[0:3], post_hash[:-4])`

IMAGE THUMBS: `https://th.easynews.com/thumbnails-%s/sm-%s.jpg % (post_hash[0:3], post_hash[:-4])`
