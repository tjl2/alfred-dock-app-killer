# alfred-dock-app-killer
When "It just works" becomes "It's just work-arounds"

macOS Sierra seems to have some weirdness with ⌘ Tab bar not showing in the UI sometimes. To fix this, the Dock app needs to be restarted. This Alfred workflow allows you to just use 'killdock' as a keyword in Alfred and it will `pkill -9 Dock` for you. macOS automatically restarts the Dock app if it exits, so this is a quick way of getting the ⌘ Tab bar to show on the desktop again.
