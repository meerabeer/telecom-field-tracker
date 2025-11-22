# Telecom Field Tracker

This single-page app reads its data from the CSV assets placed at the repository root:

- `NFOusers.csv` – NFO usernames and passwords
- `MgmtUsers.csv` – Management usernames and passwords
- `Site_Coordinates.csv` – Site IDs with latitude/longitude coordinates

Open `index.html` directly in a browser and the app will automatically load these files on startup, eliminating the need for Super Admin uploads. If credentials or sites seem missing, confirm the CSV files are present alongside `index.html` and reload the page to re-import them.
