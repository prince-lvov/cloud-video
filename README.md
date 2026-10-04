# Cloud video site

Static site for GitHub Pages.

## Deploy
1. Create a GitHub repository (e.g. `cloud-video`).
2. Upload all files from this folder to the repository root.
3. Settings → Pages → Deploy from a branch → `main` / root.
4. In Pages, set custom domain to `video.lvov.info`.
5. At the DNS provider for `lvov.info`, add CNAME: `video` → `<YOUR_GITHUB_USERNAME>.github.io`.
6. After DNS resolves, enable Enforce HTTPS.

If you want another subdomain, edit `CNAME` and use the same value in GitHub Pages settings and DNS.
