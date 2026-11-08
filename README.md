# LSP Tracker host page

The page LSPs open. It shows the LSP Tracker web app (Google Apps Script) in a full-screen frame, so Google's "This application was created by a Google Apps Script user" bar doesn't appear, and gives the app an icon for "Add to home screen".

- Live app: the `LIVE` link in `index.html`. Add `?dev` to the address to open the developer copy.
- The Apps Script `doGet` must keep `setXFrameOptionsMode(HtmlService.XFrameOptionsMode.ALLOWALL)`, or the frame stays blank.
