# Mark Six Excel Viewer

This package contains a fully Excel-driven web viewer.

## Contents
- index.html : Web viewer (no hard-coded data)
- marksix_updated_200pair_analysis.xlsx : Data source
- README.md : Usage instructions

## How to open (IMPORTANT)
You MUST open via HTTP, not file://

### Option A: GitHub Pages
Upload all files to a GitHub repository and enable Pages (main / root).

### Option B: Local HTTP server
python -m http.server 8000
Open: http://localhost:8000/index.html

## Updating data
Replace the Excel file only. Do NOT modify index.html.
