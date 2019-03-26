# Trainer App

## Getting Started

### Prereqs

- node.js
- npm
- expo




## Possible Issues
You may come across the following problems. Try the provided fixes.


If you see this response when trying to start your app with expo:

`Error: ENOSPC: System limit for number of file watchers reached`

run

`echo fs.inotify.max_user_watches=524288 | sudo tee -a /etc/sysctl.conf && sudo sysctl -p`