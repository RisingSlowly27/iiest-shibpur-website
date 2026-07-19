# IIEST Shibpur Mini College Website - Vercel Deployment

This is the production-ready static export of the IIEST Shibpur Mini College Website, pre-configured for **Vercel** deployment via **GitHub**.

## Included Pages
1. **Home Page (`/`)**: High-impact campus hero, institutional legacy, stats, news & REBECA fest updates.
2. **Faculty Directory (`/faculty/`)**: Interactive grid of 9 real professors across CST, IT, and EE departments with colored initials fallback and real-time search filters.
3. **Research Explorer (`/research/`)**: 3-pane interactive publications portal with 27 real research papers, department selectors, and faculty deep-linking.

---

## 🚀 How to Deploy to Vercel via GitHub

### Step 1: Create a GitHub Repository
1. Open terminal in this directory (`dist` folder).
2. Initialize git and commit:
   ```bash
   git init
   git add .
   git commit -m "Initial commit for IIEST Shibpur Website"
   ```
3. Push to your GitHub account:
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/iiest-shibpur-website.git
   git branch -M main
   git push -u origin main
   ```

### Step 2: Deploy on Vercel
1. Go to [Vercel.com](https://vercel.com) and log in with your GitHub account.
2. Click **Add New...** -> **Project**.
3. Select your `iiest-shibpur-website` repository.
4. Keep all default settings (Framework Preset: **Other** / **Static**).
5. Click **Deploy**.

Your website will be live on a custom `.vercel.app` URL within seconds!
