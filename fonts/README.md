# Fonts Directory

## Railey Font Installation Instructions

1. **Download the Railey font:**
   - Go to: https://www.dafont.com/railey.font
   - Click the "Download" button
   - Extract the downloaded ZIP file

2. **Add the font file to this folder:**
   - Look for a file named `Railey.ttf` or `Railey.otf` in the extracted folder
   - Copy that file and paste it into this `fonts/` directory
   - The file should be located at: `fonts/Railey.ttf` or `fonts/Railey.otf`

3. **Refresh your browser:**
   - Once the font file is in place, refresh your webpage
   - The "Ghar Se Cafe" title should now display in the Railey font

## Alternative: If you have a different font file name
If the font file has a different name (e.g., `railey-regular.ttf`), you'll need to update the CSS:
- Open `styles.css`
- Find the `@font-face` rule for Railey (near the top)
- Update the `src:` URL to match your font filename

## Troubleshooting
- Make sure the font file is directly in the `fonts/` folder (not in a subfolder)
- Check that the filename matches exactly (case-sensitive)
- Try hard-refreshing your browser (Ctrl+Shift+R or Cmd+Shift+R)
