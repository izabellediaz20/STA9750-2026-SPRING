# STA 9750 Individual Report — Teammate 4

## What's in this package
- `individual_report.qmd` — your individual report file (ready to render)
- `docs/` — folder where your rendered HTML will go

## What you need to do

### Step 1 — Add to your GitHub repo
Upload this entire folder to your GitHub repo (the same one hosting your mini-projects).

### Step 2 — Create a data/ folder
In your repo, create a `data/` folder. The report will automatically download
data from NYC Open Data on first render and save it there. You do not need to
upload any data files manually.

### Step 3 — Render the report
In R or RStudio, run:
```r
rmarkdown::render("individual_report.qmd",
                  output_file = "docs/individual_report.html")
```

### Step 4 — Push to GitHub
```bash
git add .
git commit -m "Add individual report"
git push
```

### Step 5 — Enable GitHub Pages
Go to your repo → Settings → Pages → Source: main branch → Save.
Your report will be live at:
https://YOUR_GITHUB_USERNAME.github.io/YOUR_REPO_NAME/docs/individual_report.html

### Step 6 — Submit
1. Open a GitHub issue on michaelweylandt/STA9750-2026-SPRING:
```
Hello @michaelweylandt!

My team is ready to submit our STA 9750 course project reports. You can find mine at:

- Summary Report: <http://TEAM_MEMBER_GITHUB_ID.github.io/STA9750-2026-SPRING/docs/summary_report.html>
- Individual Report: <http://YOUR_GITHUB_ID.github.io/YOUR_REPO/docs/individual_report.html>

Thanks,
@YOUR_GITHUB_ID
```

2. Upload a PDF copy of your rendered HTML to Brightspace
   (Open in Chrome → Print → Save as PDF)

