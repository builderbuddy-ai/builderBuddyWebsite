# Builder Buddy Website

## Files
- `index.html` — Home page
- `features.html` — Features with interactive WhatsApp widget
- `pricing.html` — Pricing plans
- `contact.html` — Contact form
- `signup.html` — Sign up form
- `privacy.html` — Privacy policy
- `style.css` — Shared styles
- `widget.js` — WhatsApp feature widget (used only on features.html)

## Deploy to GitHub Pages (free hosting)

1. Go to github.com and create a free account if you don't have one
2. Click **New repository**, name it `builderbuddy-ai.com`, set it to **Public**
3. Upload all these files (drag and drop them onto the repo page)
4. Go to **Settings → Pages → Source → Deploy from branch → main → / (root)**
5. GitHub will give you a URL like `https://yourusername.github.io/builderbuddy-ai.com`

## Point your domain (builderbuddy-ai.com) to GitHub Pages

In your domain registrar (wherever you bought builderbuddy-ai.com):
1. Add these 4 A records pointing to GitHub's IPs:
   - 185.199.108.153
   - 185.199.109.153
   - 185.199.110.153
   - 185.199.111.153
2. Add a CNAME record: `www` → `yourusername.github.io`
3. In GitHub Pages settings, enter your custom domain: `builderbuddy-ai.com`
4. Check **Enforce HTTPS**

DNS changes take up to 24 hours to propagate. After that your site is live at builderbuddy-ai.com — for free, forever.

## Contact form
The forms use Formspree (free tier). Sign up at formspree.io and replace `xwkgkrko` in contact.html and signup.html with your form ID.
