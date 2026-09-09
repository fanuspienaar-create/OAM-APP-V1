# OAM Studio
## One Stop Artist Marketing Studio

OAM Studio is a local-first, GitHub Pages-ready artist marketing and business workspace.

### Included in this build
- OAM branding and installable PWA shell for iPhone/Android/PC browsers
- Dashboard / Home
- Design Studio with artist poster templates and PNG export
- Photo Studio workflow and local photo editing controls
- Video Studio with local video playback, trim markers, speed and mute controls
- Audio Studio with browser voice recording and audio import
- CRM / Contacts with CSV + XLSX import, groups and export
- Quotes / Invoices with ZAR or USD, artist/business details, client details and payment status
- Print / Save as PDF invoice flow
- Marketing workspace for WhatsApp/email campaign drafting
- Local analytics
- Settings / Brand Kit / logo upload
- LocalStorage persistence and service-worker shell

### Free hosting
GitHub Pages can host this static app for free. Push the contents of this folder to a GitHub repository and enable Pages.

### No paid backend requirement
The core app stores data in the browser. No database or paid server is required for the included features.

### Important limits of a pure GitHub Pages build
A static site cannot securely send automated bulk WhatsApp messages or email campaigns by itself. This build prepares personalised campaigns and opens/copies them; true automated sending needs an approved messaging/email provider and credentials.

The Photo Studio and Video Studio are deliberately local-first. Advanced AI background removal and full FFmpeg/WebCodecs rendering can be added as local browser engines without a paid server; large model/runtime files may be downloaded by the browser.

### Spreadsheet import
The app loads the official SheetJS Community Edition browser build from its CDN when online, allowing XLSX/CSV import without a paid service.

### Deploy
1. Create a GitHub repository, e.g. `oam-studio`.
2. Upload everything in this folder to the repository root.
3. Open Settings → Pages.
4. Under Build and deployment, choose `Deploy from a branch` and select `main` / root.
5. Save and open the GitHub Pages URL.
6. On iPhone Safari use Share → Add to Home Screen; on Android Chrome use Add to Home screen / Install; on PC use the browser install icon if offered.
