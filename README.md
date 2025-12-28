# ScreenRat Versions

This repository contains the .dmg files for ScreenRat.

## Versions
- 1.0.0

## Install

Drag the .dmg file to your Applications folder.

## Uninstall

Drag the ScreenRat app from your Applications folder to the Trash.

## Troubleshooting

### "Apple could not verify ScreenRat is free of malware" or "Unidentified Developer"
This warning appears because the app is not notarized by Apple yet. To open it:

1.  **Right-click** (or Control-click) on the ScreenRat app in your Applications folder.
2.  Select **Open** from the menu.
3.  Click **Open** in the dialog box.

Alternatively, running this command in Terminal will fix it permanently:
```bash
xattr -cr /Applications/ScreenRat.app
```

## Visit
https://screenrat.app

For more information.