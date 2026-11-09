# ARES prototype

Clickable prototype of ARES, the platform for authoring, reviewing and publishing space-industry procedures. Built on the Skytek Design System.

## What's in it

- Login screen (any username and password works in this prototype)
- Dashboard: My Procedures, For review, Phase 1 Requests and Pending Implementation Reviews, with a My tasks panel
- Procedure editor: code and XML tag views, editable preview, validation while you write, steps, ref docs, image navigator, tools/parts/materials, notes, images, review comments and the lifecycle view
- Panels schedule: calendar of panel discussions and review due dates
- Reports: organisation-wide overview with CSV export
- Discrepancy notes: issues raised against procedures
- Deliveries: groups of procedures sent to operators
- Notifications: bell menu, full list with details, and notification settings
- Admin: users, groups, books, panels, RefDocs usage and notices
- Light and dark themes

## Publish on GitHub Pages

1. Create a repository and upload `index.html`, `.nojekyll` and this `README.md` to the root.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**, pick `main` and `/ (root)`, then save.
4. After a minute the site is live at `https://<your-user>.github.io/<repository>/`.

## How data works here

The prototype has no server. Everything you create is saved in your own browser (localStorage), so each visitor sees their own copy, starting from the same sample data. To start again, open the account menu (your initials, top right) and choose **Reset demo data**.

The page is a single self-contained file. Fonts load from Google Fonts; everything else, including the logo, is inside `index.html`.
