TOOLBOX v35 / GITHUB PAGES + PWA

DEPLOY
1. Extract this ZIP.
2. Upload every file and the icons folder to the root of your GitHub Pages repository.
   Required: index.html, manifest.webmanifest, sw.js, favicon.png, icons/
3. In GitHub: Settings > Pages, select the branch and root folder for publishing.
4. Open the published HTTPS URL on Android Chrome. Open Toolbox > Settings > App Install.
   If no install prompt appears, use the browser menu > Install app / Add to Home Screen.

DATA
- App records are stored locally in this browser's localStorage and IndexedDB.
- JSON export includes this room's application settings and all archive records, including images, pair profiles, pair galleries and chat logs.
- JSON export does not include the room password or recovery code.
- On another device, create/open the intended room, then use Settings > JSON Import.
- Import merges data. Existing records not in the file are kept; matching record IDs are updated from the backup.
- PWA installation does not add cloud sync. Use JSON export/import to transfer data between devices.

The visible app name is Toolbox. Historic storage keys and IndexedDB names are intentionally retained to preserve existing room data.
