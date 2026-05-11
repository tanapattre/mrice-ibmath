# IB Math Resources

A static website for IB DP Mathematics: AI SL and MYP3 teaching resources.

## What's Included

### DP Mathematics: AI SL
- **6 Scaffolded Practice Worksheets** (Probability & Statistics)
  - Sampling Methods
  - Cumulative Frequency & Box Plots
  - Descriptive Statistics
  - Probability Distributions & Expected Value
  - Tree Diagrams — Conditional Probability
  - Tree Diagrams — Percentages
- **Lesson Materials** (PPTX references)
  - Binomial Distribution
  - Discrete Random Variables 1 & 2
- **Reference Materials**
  - IB official documents
  - Publisher textbooks
  - Practice tests with markschemes

### MYP3 Mathematics
- **Unit 4: Probability**
  - Study guide
  - Criteria C & D test
  - Beyond the Unit Investigations (Criterion B enrichment)

## How to Deploy to GitHub Pages

### Step 1: Create a GitHub Repository
1. Go to [github.com](https://github.com) and log in
2. Click the **+** button → **New repository**
3. Name it `ib-math-resources` (or any name you prefer)
4. Set it to **Public** (required for free GitHub Pages)
5. Click **Create repository**

### Step 2: Upload These Files
**Option A: Drag and drop**
1. Download this folder as a ZIP file
2. Extract it
3. Go to your new GitHub repo
4. Click **Uploading an existing file**
5. Drag all files and folders into the upload area
6. Click **Commit changes**

**Option B: Command line (if you have git installed)**
```bash
cd math-resources-site
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/ib-math-resources.git
git push -u origin main
```

### Step 3: Enable GitHub Pages
1. In your repo, go to **Settings** → **Pages** (in the left sidebar)
2. Under **Source**, select **Deploy from a branch**
3. Select **main** branch and **/ (root)** folder
4. Click **Save**
5. Wait 1-2 minutes, then visit `https://YOUR_USERNAME.github.io/ib-math-resources`

## Using the Site

- **Students**: Open any worksheet, use "Student View" to see questions only
- **Teachers**: Click "Teacher View" to reveal markschemes with M1/A1/R1 marks
- **Print**: Use browser print (Ctrl/Cmd + P) — optimized for printing
- **Mobile**: Fully responsive, works on phones and tablets

## Technical Details

- **Built with**: Static HTML, CSS, MathJax (LaTeX rendering)
- **No server required**: Pure static files
- **Math rendering**: MathJax 3, loads from CDN
- **Hosting**: GitHub Pages (free)

## Updating Content

To add new worksheets or edit existing ones:
1. Edit the HTML files locally
2. Commit and push to GitHub
3. Changes go live automatically within 1-2 minutes
