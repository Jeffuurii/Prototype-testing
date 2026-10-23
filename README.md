# SKY: COTL Metrics Prototype

A browser-based prototype for the SKY: COTL testing team. The app is a static single-page site in `index.html`.

## Run it

Open `index.html` in a browser, or enable GitHub Pages after merging this branch: open **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/ (root)`, then save. GitHub Pages may take a short time to publish the site.

## Move data between devices

The prototype stores task, issue, CS ticket, and evaluation data in the current browser's local storage. That data is not synced to GitHub or shared automatically between devices.

- On the current device, open the app and choose **Export backup**. Keep the downloaded JSON backup in a private, trusted location.
- On the other device, open the same app URL and choose **Import backup** to restore it.

Backup files can contain team activity records. Do not commit them to this repository or share them publicly. The repository is public and is intended to hold the prototype code only.

For live shared data across team members and devices, the app will need a backend/database; browser backups only transfer a snapshot.
