# Surface Observer — Deploy to Vercel

## Step 1: Create a GitHub account (if you don't have one)

1. Go to [github.com/signup](https://github.com/signup)
2. Follow the steps to create a free account

## Step 2: Create a new GitHub repository

1. Go to [github.com/new](https://github.com/new)
2. Repository name: `surface-observer` (or whatever you prefer)
3. Set to **Public** (required for free Vercel hosting)
4. Click **Create repository**
5. On the next page, click **"uploading an existing file"**
6. Drag and drop the `index.html` file
7. Click **Commit changes**

## Step 3: Create a Vercel account and deploy

1. Go to [vercel.com/signup](https://vercel.com/signup)
2. Click **Continue with GitHub** (easiest — links your accounts)
3. Authorize Vercel to access your GitHub
4. You'll be taken to the Vercel dashboard
5. Click **Add New → Project**
6. Find `surface-observer` in the list and click **Import**
7. Leave all settings as default — Vercel auto-detects it's a static site
8. Click **Deploy**

## Done!

After ~30 seconds you'll get a live URL like:
```
https://surface-observer.vercel.app
```

(If the name is taken, Vercel adds a suffix like `surface-observer-xyz.vercel.app`)

You can also set a custom domain later from Vercel's project settings.

## Updating the site

Any time you update `index.html` on GitHub, Vercel will automatically redeploy within seconds.
