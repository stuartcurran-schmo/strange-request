# Strange Request

An experimental to-do list built on John Perry's idea of [structured procrastination](https://structuredprocrastination.com/).

Every note is treated as a message from a stranger: your earlier self, who wrote it in some mood with a guess about how today would go. You review each note before acting on it. You can push it down, or amend it and leave the old wording struck through.

The About screen (from the menu) explains the ideas behind each feature and the research they draw on, and says plainly that nobody has tested whether this reduces procrastination. It is a toy and an experiment.

## Run it

There is no build step. Open `index.html` in a browser.

To host it on GitHub Pages, go to Settings, then Pages, choose "Deploy from a branch", and select `main` with the `/ (root)` folder.

## Notes

- Notes are saved in the browser's local storage, on one device. Nothing is uploaded. Clearing browser data erases them.
- The Anonymous tip switch, which rewords the notes in a stranger's voice, only appears when the page runs inside Claude as an artifact. Elsewhere it stays hidden and the rest of the page works as normal.
- Fonts load from Google Fonts. The look is cyber noir throughout.
