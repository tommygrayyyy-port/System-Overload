# System Overload — private beta build

This is an installable, offline-capable web app. Training data stays in the browser on the device where it is used. The **Export Backup** button in Stats creates a file users can keep before changing devices or clearing browser data.

## Run it locally

Open this folder through a local web server, rather than double-clicking `index.html`; install and offline features require a web origin. For example, serve the folder with any simple local static-site server, then open the displayed local address on a phone and computer connected to the same network.

## Publish a private beta

1. Put the contents of this folder on a static host that provides HTTPS.
2. Visit the hosted link from a phone.
3. On iPhone Safari, choose **Share → Add to Home Screen**. On Android Chrome, choose **Install app** or **Add to Home screen**.
4. Ask every tester to export a backup before clearing browser data or switching devices.

## Test before sharing

- Complete onboarding with a new profile.
- Log a workout, close the app, and confirm the log remains after reopening.
- Export a backup, reset the data, then restore the backup.
- Confirm future dates cannot be logged or marked complete.
- Install the app and reopen it with the network turned off.

## Important current constraint

This beta has no account or cloud sync. Data does not follow a user between devices, and deleting site data deletes the local copy unless it was exported first.
