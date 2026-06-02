# Cayley & Keegan Wedding Website

This is a static wedding website: HTML, CSS, images, and a Google Forms RSVP link.

## Files To Upload

Upload the contents of this folder as the root of a GitHub repository:

- `index.html`
- `styles.css`
- `.nojekyll`
- `assets/`

## GitHub Pages Hosting

1. Create a new GitHub repository.
2. Add all files from this folder to the repository root.
3. Commit and push.
4. In GitHub, go to **Settings > Pages**.
5. Under **Build and deployment**, choose:
   - Source: `Deploy from a branch`
   - Branch: `main`
   - Folder: `/root`
6. Save.

GitHub will publish the site at a URL like:

`https://your-username.github.io/repository-name/`

## RSVP Form

The RSVP button currently links to:

`https://docs.google.com/forms/d/e/1FAIpQLSdIJFWy1S0ny8ZIkI50uWirX7MM_qqt_4DBqzutjjY_ogHV3w/viewform?usp=header`

## Local Preview

From this folder, run:

```bash
python3 -m http.server 8767
```

Then open:

`http://localhost:8767`
