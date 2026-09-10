# System Overload — private beta build

This is an installable, offline-capable web app. Training data stays in the browser on the device where it is used. The **Export Backup** button in Stats creates a file users can keep before changing devices or clearing browser data.

## Run it locally

Open this folder through a local web server, rather than double-clicking `index.html`; install and offline features require a web origin. For example, serve the folder with any simple local static-site server, then open the displayed local address on a phone and computer connected to the same network.


## Important current constraint

This beta has no account or cloud sync. Data does not follow a user between devices, and deleting site data deletes the local copy unless it was exported first.
