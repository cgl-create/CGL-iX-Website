# iX OS Website

Official project website for **iX OS by CGL+**, designed for GitHub Pages and the custom domain `ix.crazygamelabs.co.uk`.

## Deploy with GitHub Pages

1. Open **Settings → Pages** in this repository.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select branch `main` and folder `/(root)`, then save.
4. Under **Custom domain**, enter `ix.crazygamelabs.co.uk` and save.
5. In the active DNS provider for `crazygamelabs.co.uk`, configure the GitHub Pages CNAME record for host `ix` with target `cgl-create.github.io`. Do not change the apex/root or `www` records.
6. Wait for DNS verification and TLS provisioning, then enable **Enforce HTTPS** when available.

## Project status

This website describes the current project direction. The iX OS repository is at the planning and architecture stage; the website does not claim that a bootable OS or the proposed features have been implemented.

## Files

- `index.html` — responsive single-page site, styles and small progressive enhancement script are included inline.
