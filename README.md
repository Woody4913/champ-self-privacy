# Champ Self Privacy Policy

This repository contains a lightweight static privacy-policy website for Champ Self. It is designed to be hosted directly with GitHub Pages and does not use React, Next.js, npm, build tools, external JavaScript libraries, external fonts, analytics, cookies, or tracking.

## Files

- `index.html` - the public privacy policy page
- `README.md` - deployment instructions

## Contact Email

The published privacy policy currently uses `wood4913@gmail.com` as the Champ Self privacy contact. To change it later, edit the contact section in `index.html`.

## GitHub Pages Deployment

1. Create a public GitHub repository named:

   ```text
   champ-self-privacy
   ```

2. Place `index.html` and `README.md` at the repository root.

3. Go to:

   ```text
   Repository -> Settings -> Pages
   ```

4. Under **Build and deployment**, choose:

   ```text
   Source: Deploy from a branch
   Branch: main
   Folder: / (root)
   ```

5. Save.

6. The final URL should normally be:

   ```text
   https://<github-username>.github.io/champ-self-privacy/
   ```

7. Open the URL and verify it loads.

8. Paste that public URL into the WHOOP Developer Dashboard's **Privacy Policy** field.

## Updating the Policy Later

To update the privacy policy later, edit `index.html`, commit the change to the `main` branch, and push it to GitHub. GitHub Pages should automatically publish the updated page after the branch deploys.

Keep this website separate from the private Champ Self source-code repository unless you intentionally decide otherwise.
