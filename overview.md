# Overview
---

Fedora using the Sway spin. Easy migration over from i3-WM. Documentation at `man -k sway`

## Initial thoughts
* UK keyboard
* Mouse doesn't move with keyboard controls when focusing windows, but windows-focus goes after mouse. This makes it so that you need to move the mouse for it to not focus back the previous windows after a few seconds
* 


## Issues
* Serious mouse bug - randomly not interactive with certain windows
  * Best Solution [Here](https://www.reddit.com/r/Fedora/comments/1kzyr9l/warning_critical_bug_in_gnomes_mutter_483_breaks/)


## Checklist
[] Check for mouse bug above, if still there fix it
[] Enable RPM Fusion (Crucial for codecs, Steam, and hardware drivers).

[] Setup kanshi (The "Wayland replacement" for autorandr/arandr—handles multi-monitor hotplugging automatically).

[] Verify Screen Sharing (Ensure xdg-desktop-portal-wlr works for Discord/OBS/Zoom).

[] Install sway-notification-center (Or mako for a minimalist approach; replaces dunst).

[] Adopt a Wayland Launcher (Fedora defaults to rofi or wofi, but fuzzel is the current "fast/minimal" favorite).

[] Verify your Screenshot Tools
