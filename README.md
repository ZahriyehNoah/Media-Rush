# Media-Rush
Media Rush chrome extensions for screen sharing, screen recording, file sharing, youtube+audio sharing
 I'll explain how to load and test a Chrome extension in developer mode:

1. Open Chrome and go to Extensions:
   - Type `chrome://extensions` in the address bar
   OR
   - Click the three dots menu (⋮) > More Tools > Extensions

2. Enable Developer Mode:
   - Look for the "Developer mode" toggle switch in the top-right corner
   - Turn it ON

3. Load your unpacked extension:
   - Click the "Load unpacked" button that appears in the top-left
   - Navigate to your extension's directory (the folder containing manifest.json)
   - Select the folder and click "Select Folder"

4. Your extension should now be:
   - Visible in the extensions list
   - Active in Chrome (you'll see its icon in the toolbar)
   - Ready for testing

To update the extension during development:
- Make changes to your code
- Go back to chrome://extensions
- Click the refresh icon (🔄) on your extension's card
OR
- Use keyboard shortcut Ctrl+R (Windows/Linux) or Cmd+R (Mac) on the extensions page

Common troubleshooting:
- If you see errors, check the error message in the extensions page
- Verify your manifest.json is correctly formatted
- Make sure all referenced files exist in the correct locations
- Check the console for runtime errors (Right-click extension icon > Inspect)

Would you like me to explain any part in more detail?
