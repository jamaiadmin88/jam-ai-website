# JAM AI Website

Single-page landing site for JAM AI Limited.

## Before Going Live

### 1. Add your email (contact form)
1. Go to https://formspree.io and sign up (free)
2. Create a new form — set the destination email to your JAM AI email
3. Copy the form endpoint URL (looks like `https://formspree.io/f/abcdefgh`)
4. Open `index.html` and find this line:
   ```
   <form id="enquiry-form" action="ACTION_URL" method="POST">
   ```
5. Replace `ACTION_URL` with your Formspree URL

### 2. Add your JAM AI logo
- Save your logo as `jam-ai-logo.png` in this folder
- In `index.html`, find the nav logo section and replace the text logo with an `<img>` tag if desired

### 3. Connect a domain
Once you have a domain, point it to Vercel (step below).

---

## Deploy to Vercel (free)

1. Go to https://vercel.com and sign up with GitHub
2. Push this folder to a GitHub repo
3. In Vercel: New Project → Import your repo → Deploy
4. Done. You'll get a live URL like `jam-ai.vercel.app`
5. When you have a domain, add it in Vercel → Project Settings → Domains

---

## Local Preview

Just open `index.html` in your browser — no build step needed.
