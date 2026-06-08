# CT-to-MRI GitHub Pages Site

This is a GitHub Pages project page for:

**Latent Environment Navigation for CT-to-MRI Translation via Reinforcement Learning**

## What is included

- `index.html` - main website page
- `style.css` - website styling
- `assets/figures/figure-01.png` - main framework comparison figure
- `assets/figures/figure-02.png` - ALDM limited-data failure figure
- `assets/figures/figure-03.png` - Flow-guided RL method overview figure
- `.nojekyll` - disables Jekyll processing on GitHub Pages

## Important

The PDF is intentionally **not included** yet because the report is not finished.
This site only uses the figures that are already available in the current draft.

## How to upload

```bash
git clone https://github.com/KTangprapha/CT-to-MRI.github.io.git
cd CT-to-MRI.github.io

# Copy all files from this package into the repo root.

git add .
git commit -m "Add figure-only GitHub Pages site with Motivation and Method sections"
git push
```

Then enable GitHub Pages from:

`Settings -> Pages -> Deploy from a branch -> main -> /root -> Save`
