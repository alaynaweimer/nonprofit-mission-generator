# 📦 Embedding in Squarespace - Step-by-Step Guide

## Method 1: Code Block (Recommended)

### Step 1: Copy the HTML Code
1. Open `index.html` from this repository
2. Select all the code (Ctrl+A or Cmd+A)
3. Copy it to your clipboard (Ctrl+C or Cmd+C)

### Step 2: Add to Squarespace
1. Log into your Squarespace site
2. Navigate to the page where you want to add the calculator
3. Click **Edit** on the page
4. Click the **+** icon to add a new block
5. Search for and select **Code** block
6. A code editor will appear

### Step 3: Paste the Code
1. Click inside the code editor
2. Paste the entire HTML code (Ctrl+V or Cmd+V)
3. Click **Apply** or outside the code block

### Step 4: Adjust Settings
1. Make sure the code block is set to **HTML** mode (not Markdown)
2. For best display, use a **Full Width** section
3. Remove any padding if desired for a cleaner look

### Step 5: Preview and Publish
1. Click **Preview** to test the calculator
2. Try filling out the form to ensure it works
3. Test the Copy and Download buttons
4. If everything looks good, click **Save** and **Publish**

---

## Method 2: Embed Block (Alternative)

If you're hosting the file elsewhere (like GitHub Pages):

1. Get the public URL of your hosted file
2. In Squarespace, add an **Embed** block
3. Paste this code:
   ```html
   <iframe 
     src="YOUR_GITHUB_PAGES_URL" 
     width="100%" 
     height="1200px" 
     frameborder="0"
     style="border: none;">
   </iframe>
   ```
4. Adjust the height as needed

---

## Troubleshooting

### Calculator Doesn't Appear
- Make sure you're using a **Code Block**, not a Text Block
- Verify the code is set to **HTML** mode
- Check that you copied the entire file (starts with `<!DOCTYPE html>`)

### Styling Looks Off
- Squarespace may add its own CSS. Try using a **Full Width** section
- Consider using Method 2 (iframe) to isolate the styling

### Buttons Don't Work
- Make sure JavaScript is enabled in your browser
- Check the browser console (F12) for any errors
- Verify you copied the entire file including the `<script>` section

### Mobile Display Issues
- The calculator is responsive by default
- Test on actual mobile devices, not just browser resize
- Consider adjusting the section padding in Squarespace

---

## Customization Tips for Squarespace

### Matching Your Site's Branding
Before pasting the code, you can edit the colors in the CSS section:

```css
/* Find these lines and change the colors */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

Change to your brand colors:
```css
background: linear-gradient(135deg, #YOUR_COLOR_1 0%, #YOUR_COLOR_2 100%);
```

### Adjusting Width
The calculator has a max-width of 900px. To change:

```css
.container {
    max-width: 900px; /* Change this value */
}
```

### Removing the Gradient Background
If you want the calculator to blend with your Squarespace page:

```css
body {
    background: transparent; /* or your site's background color */
    padding: 0; /* removes outer padding */
}
```

---

## Best Practices

1. **Use Full Width Sections** - The calculator looks best with room to breathe
2. **Test on Mobile** - Always preview on actual mobile devices
3. **Keep It Updated** - If you update the GitHub version, update Squarespace too
4. **Add Context** - Consider adding a text block above explaining what the tool does

---

## Adding to Multiple Pages

To use on multiple pages without duplicating code:

1. Host the calculator on GitHub Pages (see main README)
2. Use the iframe embed method (Method 2 above)
3. Update the hosted version once, and all pages update automatically

---

## Performance Notes

- The calculator is lightweight (single HTML file)
- No external dependencies means fast loading
- All resources are inline (no separate CSS/JS files to load)

---

## Need Help?

If you run into issues:
1. Check the Squarespace Help Center for Code Block documentation
2. Open an issue on GitHub
3. Test the calculator outside Squarespace first (open index.html locally)

---

**Pro Tip:** Save a copy of the HTML code in a safe place before pasting into Squarespace, so you can easily revert or update later!
