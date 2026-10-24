# Personal website starter 

This is a responsive static personal profile website intended for GitHub Pages and a custom domain registered with GoDaddy.

## Files
- `index.html` — page content
- `style.css` — responsive visual styling

## Publish using GitHub Pages
1. Sign in to GitHub or create an account at https://github.com.
2. Create a **public** repository. For a simple personal site, a repository named `YOUR-GITHUB-USERNAME.github.io` is a convenient choice.
3. Upload `index.html` and `style.css` to the repository root and commit the changes.
4. Open repository **Settings → Pages** and select the branch and root folder as the publishing source, then save.
5. Wait for the GitHub Pages URL to appear and test it before connecting your custom domain.

## Connect your GoDaddy domain
1. In the repository, open **Settings → Pages**.
2. In **Custom domain**, enter your actual domain (for example, `example.com`) and save. Do not use the example domain; replace it with the domain you own.
3. In GoDaddy, open **Domain Portfolio → your domain → DNS**.
4. Follow GitHub's current official guide for the exact DNS records: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site
5. Keep existing email-related DNS records (MX, SPF, DKIM, etc.) unless you know they conflict. Do not change nameservers just for this setup.
6. Once DNS checks pass in GitHub Pages settings, enable **Enforce HTTPS**.

DNS propagation and HTTPS certificate provisioning can take some time.

## Before publishing
- Replace any generic wording with accurate career achievements and quantified impact.
- Check the LinkedIn URL and contact details.
- If you want a profile photo, add the image to the repository and update the HTML.
- Do not publish private contact details you do not want public.

This website is a static profile; it does not include a database, login, or contact-form backend.
