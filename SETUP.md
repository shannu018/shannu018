# 🚀 How to Deploy Your GitHub Profile README (`shannu018`)

Your new hyper-advanced GitHub profile has been fully generated locally! Follow these simple steps to publish it live to your GitHub profile (`https://github.com/shannu018`).

---

## 📌 Step 1: Create the GitHub Repository

1. Go to GitHub: **[https://github.com/new](https://github.com/new)**
2. In the **Repository name** field, type exactly: **`shannu018`**
   *(GitHub will display a banner saying: "You found a secret! `shannu018/shannu018` is a special repository...")*
3. Select **Public**.
4. **Do NOT** initialize with a README, .gitignore, or license (keep it empty).
5. Click **Create repository**.

---

## 📌 Step 2: Push the Code from Your Terminal

Open PowerShell / Terminal in `C:\Users\Shannu\.gemini\antigravity\scratch\github-profile-shannu018` and run the following commands:

```powershell
# Navigate to the folder
cd C:\Users\Shannu\.gemini\antigravity\scratch\github-profile-shannu018

# Initialize Git
git init

# Add all files (README.md, assets, workflows)
git add .

# Commit changes
git commit -m "feat: initial commit of ultra-advanced GitHub profile README"

# Rename branch to main
git branch -M main

# Link to your GitHub repository
git remote add origin https://github.com/shannu018/shannu018.git

# Push to GitHub
git push -u origin main
```

---

## 📌 Step 3: Enable the Contribution Snake GitHub Action

The GitHub Action workflow (`.github/workflows/snake.yml`) will automatically run every day at midnight to generate your dynamic snake animation.

To trigger it manually the first time:
1. Go to **`https://github.com/shannu018/shannu018/actions`**
2. Click on **`Generate Contribution Snake Animation`** on the left menu.
3. Click **`Run workflow`** -> **`Run workflow`**.
4. Once completed, a new `output` branch will be created containing `snake-dark.svg`, and it will immediately render on your GitHub profile page!

---

## 🎨 File Inventory

```
github-profile-shannu018/
├── README.md                    # Master Profile README
├── SETUP.md                     # Deployment & Customization Guide
├── .github/
│   └── workflows/
│       └── snake.yml            # Automated Snake SVG Generator Action
└── assets/
    ├── banner.svg               # Cyberpunk Animated Header Banner
    ├── terminal.svg             # Interactive CLI Terminal Mockup
    ├── agent-swarm.svg          # Multi-Agent Architecture Diagram
    ├── rag-pipeline.svg         # RAG Vector Pipeline Diagram
    ├── separator.svg            # Glowing Section Divider
    ├── footer.svg               # Animated Footer CTA Banner
    ├── section-identity.svg     # Core Identity Header SVG
    ├── section-featured.svg     # Featured Systems Header SVG
    ├── section-projects.svg     # Selected Projects Header SVG
    ├── section-tech.svg         # Technology Systems Header SVG
    ├── section-telemetry.svg    # System Telemetry Header SVG
    ├── section-vector.svg       # Current Vector Header SVG
    ├── icon-ai.svg              # AI Core Icon
    ├── icon-systems.svg         # Systems Icon
    └── icon-web.svg             # Full-Stack Web Icon
```
