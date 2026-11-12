HANJO AND CREWBOARD — iPHONE / WEB PROTOTYPE

Open index.html in a modern browser. For iPhone, host these files on HTTPS, open the site in Safari, tap Share, then Add to Home Screen. The service worker enables offline loading after the first successful visit.

Features: responsive overview, crew and hours view, daily/weekly work leaderboard, work report form, optional image selection, opt-in job-site GPS check-in, local-device saving, and downloadable JSON backup.

IMPORTANT LIMITATIONS
- This is a prototype, not an authenticated multi-user company system. Each browser/device has its own local data; entries do not sync to managers or coworkers.
- Seed workers, jobs, hours and work updates are fictional demo data. Replace them before operational use.
- Photos are not uploaded or stored; the selected filename can be included in local work updates only if the browser retains it during the session.
- Location is read only after a worker taps the check-in button and grants permission. HTTPS is required for geolocation on iPhone.
- Do not use for payroll or employee monitoring until a secure backend, worker accounts, data-retention rules and access controls are added.
- Netlify project hanjo-crewboard has also been reserved, but its direct deployment route requires a local Netlify CLI.

Files: index.html, manifest.webmanifest, sw.js, icon.svg, README.txt.