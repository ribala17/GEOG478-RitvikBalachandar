# GitHub Upload Instructions for Lab 6

## Step-by-Step Guide to Upload Files to GitHub

### Option 1: Using GitHub Web Interface (Easiest)

1. **Create a new Repository**
   - Go to https://github.com/new
   - Repository name: `TAMU-GEOG-678-WebGIS-Lab06` (or your preferred name)
   - Description: "TAMU WebGIS Lab 6 - Advanced Javascript Mapping with Leaflet JS"
   - Make it Public or Private (your choice)
   - Click "Create repository"

2. **Upload Files**
   - Click "Add file" → "Upload files"
   - Drag and drop all files from `lab06` folder:
     - Custom_Map.html
     - Tutorial1_GeoJSON.html
     - Tutorial2_Choropleth.html
     - tamubuildings.js
     - README.md
   - Click "Commit changes"

3. **Get Your Repository Link**
   - Your repository URL will be: `https://github.com/[your-username]/[repository-name]`
   - Copy this link to submit on eCampus

### Option 2: Using Git Command Line

1. **Initialize Local Repository**
   ```
   cd c:\Users\ritvi\Downloads\lab06
   git init
   git add .
   git commit -m "Initial commit: TAMU WebGIS Lab 6 files"
   ```

2. **Create Repository on GitHub**
   - Go to https://github.com/new
   - Create repository named `TAMU-GEOG-678-WebGIS-Lab06`
   - DO NOT initialize with README (we already have one)

3. **Push to GitHub**
   ```
   git remote add origin https://github.com/[your-username]/[repository-name].git
   git branch -M main
   git push -u origin main
   ```

### Option 3: Using GitHub Desktop App

1. Download GitHub Desktop from https://desktop.github.com
2. Sign in with your GitHub account
3. Click "Create New Repository"
4. Choose local path to your `lab06` folder
5. Make your first commit with all files
6. Publish to GitHub

## Troubleshooting

**Issue: Files won't display in browser from GitHub**
- Solution: Use GitHub Pages to host the maps
  1. Go to Repository Settings → Pages
  2. Select "main" branch as source
  3. Your files will be available at: `https://[your-username].github.io/[repository-name]/`

**Issue: Maps show blank/error**
- Make sure all three HTML files and tamubuildings.js are in the same directory
- Check browser console for errors (F12)
- Verify you have internet connection for map tiles

**Issue: TAMU buildings not showing**
- Ensure tamubuildings.js is properly loaded
- Check that the external CDN links are accessible
- Try downloading the full tamubuildings.js file from:
  https://raw.githubusercontent.com/tamu-edu-students/2025-TAMU-GEOG-678-WebGIS-MGsc/main/labs/tamubuildings.js

## Verifying Your Submission

Before submitting, verify:
- ✅ All three HTML files are working
- ✅ Maps display correctly in browser
- ✅ Interactivity works (hover, click, zoom)
- ✅ Repository is publicly accessible
- ✅ All files are in the main directory (no nested folders)
- ✅ README.md is included
- ✅ Link to repository is ready to submit

## Final Submission

1. **Screenshots**
   - Open each HTML file in browser
   - Take screenshots of:
     - Tutorial1_GeoJSON.html with visible GeoJSON features
     - Tutorial2_Choropleth.html showing US states
     - Custom_Map.html showing TAMU campus buildings
   - Upload screenshots to eCampus

2. **GitHub Link**
   - Copy repository URL: `https://github.com/[your-username]/[repository-name]`
   - Paste link in eCampus submission

## File Structure

Your GitHub repository should have this structure:
```
your-repo/
├── Custom_Map.html
├── Tutorial1_GeoJSON.html
├── Tutorial2_Choropleth.html
├── tamubuildings.js
└── README.md
```

Good luck with your submission! 🎓
