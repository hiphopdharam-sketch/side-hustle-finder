# dharambuilds Side Hustle Finder
## Deploy in 5 Minutes — Step by Step

### FILES TO UPLOAD (exact structure):
```
index.html        ← ROOT folder
vercel.json       ← ROOT folder
api/
  chat.js         ← inside "api" folder
```

### STEP 1 — Get Free Anthropic API Key
1. Go to: https://console.anthropic.com
2. Sign up free → API Keys → Create Key → Copy it

### STEP 2 — Upload to GitHub
1. Go to github.com → New repository → name: side-hustle-finder → Create
2. Click "uploading an existing file"
3. Upload: index.html and vercel.json to ROOT
4. Create "api" folder → upload chat.js inside it
5. Commit changes

### STEP 3 — Deploy on Vercel
1. Go to vercel.com → Sign up with GitHub
2. Add New Project → Select side-hustle-finder repo
3. Leave all settings default → Deploy

### STEP 4 — Add API Key in Vercel
1. Project → Settings → Environment Variables
2. Name: ANTHROPIC_API_KEY  |  Value: your key
3. Save → Deployments → Redeploy

### STEP 5 — Done!
Your live link: https://side-hustle-finder.vercel.app
Put it in your Instagram bio!
