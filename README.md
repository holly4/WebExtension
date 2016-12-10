###WebExtension - Sample Web Extension to work across compatible browsers

Web Extension support based on Chrome Extensions is now in these browsers

- Google Chrome (obviously)
- Firefox
- Microsoft Edge
- Opera

This repository explores creating a simple Web Extension to work across all four browsers.

The intended functionality is:

 1. Run on pages at example.org. 
 2. Add a button in the content script and popup to send messages to each other. 
 3. Log messages in the web page and the pop-ui
 4. Store a setting and allow access on an options page controlling whether the content script is automatically injected or only when the first message is sent from the popup.
