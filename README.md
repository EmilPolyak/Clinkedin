# Clinkedin
Scrolling bug (up-down while filtering) fixed om 1.0.7 



# Clinkedin

A Chrome extension for filtering and customizing your LinkedIn feed, inspired by F.B. Purity. 
Note: this extension was not designed for the native Linkedin phone app. It works in browser environments only.

## What you can control

- Hide posts containing specific words, phrases, hashtags, or links to certain websites.
- Mute authors or companies. Keep only 1st connections and followed authors, or include 2nd connections too.
- Hide sponsored posts, suggestions, reposts, polls, videos, and other post types.
- Hide sidebars, the post composer, engagement counts, or action buttons. Widen the feed or reduce spacing.
- Disable video autoplay while keeping manual Play available.

Filters and appearance changes are off until you enable them.

## Install

Requires desktop Chrome 111 or later.

1. Download the **Clinkedin release ZIP** and extract it to a folder you will keep.
2. Open `chrome://extensions` in Chrome.
3. Turn on **Developer mode**.
4. Click **Load unpacked** and select the extracted folder containing `manifest.json`.
5. Pin **Clinkedin** from Chrome's Extensions menu, then refresh LinkedIn.
6. Click the Clinkedin icon, open **Settings**, choose your filters, and click **Save changes**.

## Everyday controls

- **Show/Hide filtered content:** Below autoplay in the popup. On shows reason bars with **Show post / Hide post** buttons. Off removes filtered posts and their bars completely. Saves immediately.
- **Disable video autoplay:** Stops automatic playback; click Play to watch. Some players may still show a brief preview.
- **Pause or reveal:** Pause Clinkedin or temporarily reveal filtered posts from the popup. Pausing also turns off autoplay blocking.
- **Backups:** Use **Export JSON** in Settings. Restore with **Import JSON**, then **Save changes**.

Enter words, phrases, and author names one per line. Always-allow rules override blocking filters. If a followed author is incorrectly hidden, add their exact name to **Additional followed authors**.

## Update

1. Export your settings as a backup.
2. Extract the new release ZIP into your existing extension folder, replacing the old files.
3. Open `chrome://extensions` and click **Reload** on Clinkedin.
4. Refresh LinkedIn.

Keep the same folder location; there is no need to uninstall.

## Privacy and practical notes

Settings stay in your Chrome profile. Clinkedin has no analytics and does not send your posts or preferences anywhere.

Filters and layout controls apply to the home feed; autoplay control applies across LinkedIn. Filters read loaded post text. Some depend on English labels. LinkedIn updates may affect how they work.

If something stops working, reload Clinkedin and refresh LinkedIn. Include your Chrome and Clinkedin versions when reporting problems.

