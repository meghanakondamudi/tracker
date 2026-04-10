# tracker
Masterfile

# Life Tracker

A personal life journal and to-do tracker across 6 life areas — hosted as a single HTML file on GitHub Pages.

## Features
- 📝 Notes & to-dos per life area (Career, Health, Relationships, Learning, Finance, Mindset)
- 📅 Year / Quarter / Month views with navigation
- ✅ Check off to-dos, track completion %
- 📊 Stats strip showing entries, notes, tasks, and progress
- 💾 Data saved in browser (localStorage) — no server needed
- ↓ Export your data as a CSV at any time
- ↑ Import a CSV to restore or migrate data

---

## Hosting on GitHub Pages (free, takes 3 minutes)

### Step 1 — Create a GitHub account
Go to [github.com](https://github.com) and sign up if you don't have an account.

### Step 2 — Create a new repository
1. Click the **+** icon → **New repository**
2. Name it `life-tracker` (or anything you like)
3. Set it to **Public** (required for free GitHub Pages)
4. Click **Create repository**

### Step 3 — Upload the file
1. In your new repo, click **Add file** → **Upload files**
2. Drag and drop `index.html` into the upload area
3. Click **Commit changes**

### Step 4 — Enable GitHub Pages
1. Go to your repo's **Settings** tab
2. In the left sidebar, click **Pages**
3. Under "Branch", select `main` and folder `/ (root)`
4. Click **Save**

### Step 5 — Visit your site
After ~1 minute, your app will be live at:
```
https://YOUR-USERNAME.github.io/life-tracker/
```

---

## Backing up your data

Your entries are stored in your **browser's localStorage** — they stay on your device.

To back up or move to another device:
1. Click **Export to CSV** in the sidebar → saves a `.csv` file
2. On your new device/browser, open the app and click **Import CSV**

To open the CSV in Excel or Google Sheets, just open it normally — all columns are labelled.

---

## CSV format

| Column | Description |
|--------|-------------|
| `id` | Unique entry ID |
| `title` | Entry title |
| `area` | Life area (career / health / relations / learning / finance / mindset) |
| `type` | `note` or `todo` |
| `date` | Date (YYYY-MM-DD) |
| `done` | `true` or `false` (for to-dos) |
| `body` | Entry body text |

---

## Tips

- **Year view** — click any quarter block to drill into that quarter
- **Filter bar** — toggle areas on/off in year and month views  
- **Expand entries** — click an entry card to expand the full body text
- **Edit / Delete** — hover an entry card to reveal edit ✎ and delete ✕ buttons
