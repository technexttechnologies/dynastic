# Dynastic Moves Dance Studio — Website

A premium dark-themed website for **Dynastic Moves Dance Studio**, Wayanad, Kerala.

## 🚀 Deploy to Vercel

### Option 1: Vercel CLI (Recommended)

1. **Install Vercel CLI**
   ```bash
   npm install -g vercel
   ```

2. **Login to Vercel**
   ```bash
   vercel login
   ```

3. **Deploy from this folder**
   ```bash
   cd dynastic-moves
   vercel
   ```

4. Follow the prompts — your site will be live in seconds.

---

### Option 2: Drag & Drop (Easiest)

1. Go to [vercel.com](https://vercel.com) and sign in.
2. Click **"Add New → Project"**.
3. Drag and drop this entire `dynastic-moves` folder into the upload area.
4. Click **Deploy** — done!

---

### Option 3: GitHub + Vercel (Best for updates)

1. Push this folder to a GitHub repository.
2. Go to [vercel.com](https://vercel.com) → **Add New Project**.
3. Import your GitHub repo.
4. Vercel auto-detects the static site — click **Deploy**.
5. Every future `git push` will auto-redeploy.

---

## 📁 Project Structure

```
dynastic-moves/
├── index.html      ← Main website (all-in-one)
├── vercel.json     ← Vercel deployment config
└── README.md       ← This file
```

## ✏️ Customization

All content, styles, and scripts are in `index.html`.

- **Phone numbers** → Search for `+91 98765 4321`
- **Emails** → Search for `dynasticmoves.in`
- **Address** → Search for `Main Road, Kalpetta` / `Town Centre, Mananthavady`
- **Colors** → Edit CSS variables at the top (`:root { --red: #c8102e; ... }`)

## 🌐 Custom Domain (After Deploy)

1. In Vercel dashboard → your project → **Settings → Domains**
2. Add your domain (e.g. `dynasticmoves.in`)
3. Update your DNS records as shown by Vercel
