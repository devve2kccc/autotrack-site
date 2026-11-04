# AutoTrack — GitHub Pages site

Dummy landing page used as the Supabase **Site URL** for AutoTrack.

## Publish

1. Create a **public** repository on GitHub named `autotrack-site`.
2. From this folder:

```bash
git init
git add .
git commit -m "Add AutoTrack landing page"
git branch -M main
git remote add origin git@github.com:devve2kccc/autotrack-site.git
git push -u origin main
```

3. In the repo: **Settings → Pages → Build and deployment**
   - Source: **Deploy from a branch**
   - Branch: **main**, folder: **/ (root)**
   - Save

4. Wait 1–2 minutes. The URL will be:

```
https://devve2kccc.github.io/autotrack-site/
```

## Use it in Supabase

**Authentication → URL Configuration → Site URL:**

```
https://devve2kccc.github.io/autotrack-site/
```

**Redirect URLs** (optional, for the Expo app / future deep links):

```
autotrack://**
autotrack://login-callback
http://localhost:3000/**
```

The page is static: no build step, no dependencies.
