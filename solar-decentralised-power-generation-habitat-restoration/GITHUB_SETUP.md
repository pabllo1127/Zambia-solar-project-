# How to push this to GitHub

## Repository name

**GitHub repo name (URL-safe, no spaces):**
```
solar-decentralised-power-generation-habitat-restoration
```

**Full display title (shown in README.md):**
```
Using Solar Energy for Decentralised Power Generation in a Cost-Effective Manner and Habitat Restoration
```

---

## Step 1 — Create the repo on GitHub

1. Go to https://github.com/new
2. **Repository name:** `solar-decentralised-power-generation-habitat-restoration`
3. **Description:** `Using solar energy for decentralised power generation in a cost-effective manner and habitat restoration — Zambia case study with ZESCO JV structure, agrivoltaics, and developer roadmap`
4. Set to **Public** (shows on your profile) or Private
5. Do **NOT** tick "Add a README file" — you already have one
6. Click **Create repository**

---

## Step 2 — Push from your computer

Extract the zip, open a terminal inside the extracted folder, then run:

```bash
git init
git add .
git commit -m "initial commit: decentralised solar power generation and habitat restoration — Zambia case study"
git remote add origin https://github.com/YOUR_USERNAME/solar-decentralised-power-generation-habitat-restoration.git
git branch -M main
git push -u origin main
```

Replace `YOUR_USERNAME` with your actual GitHub username.

---

## Step 3 — Verify it looks right

Visit:
```
https://github.com/YOUR_USERNAME/solar-decentralised-power-generation-habitat-restoration
```

The README.md renders automatically as the repo homepage.
Check the folder structure matches what is described in the README.

---

## Optional — GitHub Pages (live HTML visualizations)

To host the interactive charts as live web pages:

1. Go to your repo → **Settings** → **Pages**
2. Source: **main branch**, / (root) folder
3. Save

Your visualizations will be live at:
```
https://YOUR_USERNAME.github.io/solar-decentralised-power-generation-habitat-restoration/visualizations/02_scale_to_cost_chart.html
https://YOUR_USERNAME.github.io/solar-decentralised-power-generation-habitat-restoration/visualizations/03_feasibility_dashboard.html
https://YOUR_USERNAME.github.io/solar-decentralised-power-generation-habitat-restoration/visualizations/04_zesco_jv_roadmap.html
https://YOUR_USERNAME.github.io/solar-decentralised-power-generation-habitat-restoration/visualizations/05_developer_roadmap.html
```

---

## Repo structure

```
solar-decentralised-power-generation-habitat-restoration/
├── README.md
├── GITHUB_SETUP.md                    ← this file
├── paper/
│   └── zambia_solar_academic_paper.docx
├── docs/
│   ├── 01_project_scope.md
│   ├── 02_zambia_context.md
│   ├── 03_to_07_technical_sections.md
│   └── 08_09_jv_and_roadmap.md
├── data/
│   └── all_research_tables.md
└── visualizations/
    ├── 02_scale_to_cost_chart.html
    ├── 03_feasibility_dashboard.html
    ├── 04_zesco_jv_roadmap.html
    └── 05_developer_roadmap.html
```
