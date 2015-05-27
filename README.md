Pomf uploader for linux
=====================

Takes screenshots and uploads them to a pomf-like service and copies the link to clipboard. Recommended for set up with keyboard shortcuts
<br>Utilises __gnome-screenshot__ for taking screenshots, __zenity__ for file uploads (both included in Ubuntu).

## Instructions
- Clone or download the repo
- Make it executable using __chmod +x poomf__
- Place this file wherever you want (recommended: /usr/local/bin)
- Set up keyboard shortcuts within linux
  - (in Ubuntu it's system settings > keyboard > keyboard shortcuts > custom shortcuts)
  - Log out for the changes to take place

### Usage
```
_____________ poomf for linux _____________
Usage:
  poomf [OPTIONS] [PATH]

OPTIONS:
  -d                 poomf entire desktop
  -a                 poomf selected area
  -w                 poomf current window
  -c                 poomf clipboard content
  -f                 poomf specific file (opens file dialog)

  --help,-h          show this page

PATH:
  PATH               optional: path of file to poomf
```

## Dependencies
- gnome-screenshot
- zenity
- curl
- xclip
- notify-send
