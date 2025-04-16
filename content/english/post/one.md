+++
date = '2025-04-12T21:09:58+03:00'
description = 'Step by Step.'
draft = true
title = 'How do I Install and Update Ungoogled Chromium on Windows?'
featured_image= "/images/chromium.jpg"
tags= 'guide'
+++

Now that you've finally made the decision to switch; here's the how-to:
>1. Install <a href="/downloads/ungoogled-update.bat" download>ungoogled-update.bat</a>

>1,5. Your browser may block this install (because it's a file that executes a command), so select "Keep" on Chrome or other browsers based on chromium (vivaldi, opera, brave, etc...)

>2. Run it (double click)

>3. Click "y" if prompted

And you're done. Windows will handle the rest.

What's written in this command, if you don't trust: "winget install --id=eloston.ungoogled-chromium -e"

This is code directly from Ungoogled Chromium's github: https://github.com/ungoogled-software/ungoogled-chromium-windows

You can specifically check what's in the file if you: 
> Right click on the .bat file > edit with notepad
and you'll see what's in it.

## How do I set auto updates up in UC?

1. Shift + right click on your ungoogled-update.bat file
2. Find and click on "Add Shortcut"
3. Now you should have "ungoogled-update.bat - Shortcut"
4. Press win + R (windows key and R)
5. Type shell:startup, press enter
6. Drag and drop "ungoogled-update.bat - Shortcut" in the folder that has opened.

And now ungoogled-update.bat should start on every login. The command panel might momentarily boot itself up on login. 
