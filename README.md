# 📱 — APK Download Website

100% FREE APK download landing page with GitHub-based remote config.

## 🔥 How It Works

```
config.json (GitHub) → Website fetches latest APK link → User downloads directly
```

Client edits `config.json` on GitHub → Website auto-updates. No redeploy needed!

## 📁 Files

| File | Description |
|------|-------------|
| `index.html` | Main download website |
| `config.json` | APK link config (client edits this) |
| `guide.html` | Client guide (Hindi) |
| `setup.html` | Developer setup guide |
| `vercel.json` | Vercel routing |

## ⚙️ Setup

1. Update `GITHUB_USER` and `GITHUB_REPO` in `index.html`
2. Update edit links in `guide.html`
3. Push to GitHub
4. Connect to Vercel → Deploy

## 📱 Client Daily Routine

1. Upload new APK to GitHub Releases
2. Copy the link
3. Edit `config.json` → Paste new link → Commit
4. Done! Website updated!

## 💰 Cost

**$0** — Everything is free (GitHub + Vercel)

## 📄 License

MIT
