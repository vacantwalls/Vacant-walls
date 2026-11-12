# Vacant Walls website

A static site: one `index.html` file, no build step.

## Deploy to Vercel (auto-updates on every push)

1. Put this folder in a Git repo and push it to GitHub:
   ```
   git init
   git add .
   git commit -m "Vacant Walls site"
   git branch -M main
   git remote add origin https://github.com/<your-username>/vacant-walls.git
   git push -u origin main
   ```
2. In Vercel, choose **Add New → Project**, import the repo, leave Framework Preset as **Other**, leave Build Command and Output Directory empty, and click **Deploy**.
3. From then on, every push to `main` goes live at your Vercel URL within about 30 seconds. Every other branch or pull request gets its own preview link.

## Day to day

Edit `index.html`, then:
```
git add . && git commit -m "update" && git push
```

## Before launch

- Replace `admin@vacantwallsgallery.com` and `@vacantwalls` with your real email and Instagram.
- The invite, RSVP, email list and artist forms only show a confirmation message. Connect each to a form service (Formspree, Google Forms, Kit or Mailchimp) so submissions reach you.
- Replace the placeholder artists, artworks and descriptions.
- Add your domain under Vercel project **Settings → Domains**.
