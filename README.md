# RoleDesk marketing site

Static landing page for RoleDesk, built from `marketing/` in the main
`roledesk-sellable` repo and deployed here via GitHub Pages.

This repo contains only the built site (no application source). To
redeploy after a content change, rebuild `marketing/` in the main repo
(`npm run build`) and copy `dist/index.html`, `dist/assets`,
`dist/brands`, `dist/vendor` here, then commit and push.
