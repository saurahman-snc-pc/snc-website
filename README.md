# Saudi Nexogen Company website

Static website for saudinexogen.com. No build step: upload these files as they are.

## Publish on GitHub Pages (free)

1. Sign in to github.com as saurahman-snc-pc and create a new public repository named `snc-website`.
2. Click **uploading an existing file**, drag in everything from this folder (index.html, README.md and the img folder), then click **Commit changes**.
3. Open **Settings > Pages**. Under **Build and deployment**, set Source to **Deploy from a branch**, Branch to **main** and folder to **/ (root)**, then **Save**.
4. After a minute or two the site is live at https://saurahman-snc-pc.github.io/snc-website/ . Share this link for review.

## Connect saudinexogen.com (after approval)

1. In **Settings > Pages > Custom domain**, enter `saudinexogen.com` and save.
2. At your domain registrar, add the DNS records GitHub shows (A records for the root domain and a CNAME for www).
3. Do not change the MX records: they carry the company email (info@saudinexogen.com).
4. When the domain check passes, tick **Enforce HTTPS**.

## Still to replace

- Photos in img/ are temporary Unsplash images: replace with real SNC site photos, keeping the same file names.
- WhatsApp button: add the business WhatsApp number.
- Arabic version: included (EN / عربي switch in the header); have a native speaker review the wording before launch.
