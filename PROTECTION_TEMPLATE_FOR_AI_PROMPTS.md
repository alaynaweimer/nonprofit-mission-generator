# 🛡️ Standard Calculator Protection Prompt

## Copy-Paste This Into Every Calculator Creation Request

---

## PROTECTION REQUIREMENTS FOR ALL CALCULATORS

**CRITICAL: Include the following brand protection and licensing elements in EVERY calculator you create:**

### 1. COPYRIGHT NOTICE (HTML Comment at top)
Place this immediately after `<!DOCTYPE html>`:

```html
<!--
═══════════════════════════════════════════════════════════════════════
  [CALCULATOR NAME]
  
  Copyright © 2025 IEF Fractional Services | Alayna Weimer
  All Rights Reserved.
  
  Licensed under Creative Commons Attribution-NonCommercial-NoDerivatives 4.0
  https://creativecommons.org/licenses/by-nc-nd/4.0/
  
  ✓ FREE for nonprofit organizations
  ✓ FREE for personal, non-commercial use
  ✗ COMMERCIAL USE PROHIBITED without license
  ✗ MODIFICATIONS PROHIBITED
  ✗ REDISTRIBUTION PROHIBITED
  
  This tool is part of the Nonprofit Toolkit Hub.
  
  For commercial licensing inquiries:
  Email: [your-email@example.com]
  Website: [your website]
  
  Unauthorized commercial use, modification, or redistribution is 
  prohibited and will be enforced.
  
  Created with ❤️ for nonprofit leaders everywhere.
═══════════════════════════════════════════════════════════════════════
-->
```

### 2. HEADER BRANDING
Include in the calculator header:

```html
<div class="header">
    <div style="font-size: 0.9em; margin-bottom: 10px; opacity: 0.95;">
        Powered by <strong>IEF Fractional Services</strong>
    </div>
    <h1>[Calculator Icon] [Calculator Name]</h1>
    <p>[Calculator tagline/description]</p>
    <p style="font-size: 0.85em; margin-top: 10px; opacity: 0.9;">
        Part of the Nonprofit Toolkit Hub by Alayna Weimer
    </p>
</div>
```

### 3. LICENSE BANNER (Prominent box near top)
Include after header, before main content:

```html
<div style="background: linear-gradient(135deg, #e3f2fd 0%, #f3e5f5 100%); border: 2px solid #667eea; padding: 20px; border-radius: 12px; margin-bottom: 25px; box-shadow: 0 4px 12px rgba(102, 126, 234, 0.15);">
    <div style="text-align: center; margin-bottom: 12px;">
        <strong style="font-size: 1.1em; color: #2c3e50;">
            © 2025 IEF Fractional Services | Alayna Weimer
        </strong>
    </div>
    <div style="text-align: center; font-size: 0.95em; color: #5a6c7d; line-height: 1.8;">
        Licensed under 
        <a href="https://creativecommons.org/licenses/by-nc-nd/4.0/" target="_blank" style="color: #667eea; text-decoration: none; font-weight: 600;">
            CC BY-NC-ND 4.0
        </a>
        <br>
        <span style="color: #4caf50; font-weight: 600;">✓ Free for Nonprofits</span> | 
        <span style="color: #667eea; font-weight: 600;">Commercial License Available</span>
        <br>
        <a href="mailto:[your-email@example.com]" style="color: #667eea; text-decoration: none; font-size: 0.9em;">
            Contact for Commercial Licensing
        </a>
    </div>
</div>
```

### 4. FOOTER BRANDING
Include at bottom before closing </body>:

```html
<footer style="text-align: center; padding: 40px 20px; color: white; background: rgba(0,0,0,0.2); margin-top: 40px;">
    <div style="max-width: 800px; margin: 0 auto;">
        <div style="font-size: 1.1em; font-weight: 600; margin-bottom: 15px;">
            🌟 IEF Fractional Services
        </div>
        <div style="font-size: 0.95em; line-height: 1.8; margin-bottom: 20px;">
            Empowering nonprofits with professional Financial, HR, and Operations support
        </div>
        <div style="font-size: 0.85em; opacity: 0.9; margin-bottom: 15px;">
            Created by <strong>Alayna Weimer</strong> | Bend, Oregon
        </div>
        <div style="font-size: 0.8em; opacity: 0.85; border-top: 1px solid rgba(255,255,255,0.3); padding-top: 15px; margin-top: 15px;">
            This tool is part of the <strong>Nonprofit Toolkit Hub</strong><br>
            © 2025 IEF Fractional Services. Licensed under CC BY-NC-ND 4.0.<br>
            Free for nonprofits. Commercial licensing available.
        </div>
    </div>
</footer>
```

### 5. PDF/EXPORT BRANDING
If calculator has download/export functionality, include branding in exports:

```javascript
const exportContent = `
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>[Export Title]</title>
    <style>
        /* styling */
    </style>
</head>
<body>
    <div class="header">
        <div class="branding">IEF Fractional Services</div>
        <div class="creator">[Calculator Name] by Alayna Weimer</div>
    </div>
    
    <div class="content">
        ${userContent}
    </div>
    
    <div class="footer">
        Generated on ${new Date().toLocaleDateString()}
        <br>
        <strong>Nonprofit Toolkit Hub</strong>
        <div class="copyright">
            © 2025 IEF Fractional Services | CC BY-NC-ND 4.0 License
            <br>
            For more tools and resources, contact Alayna Weimer
        </div>
    </div>
</body>
</html>
`;
```

### 6. COLOR SCHEME (Standard across all calculators)
```css
Primary: #667eea (purple/blue)
Secondary: #764ba2 (purple)
Background: #f5f7fa (light gray)
Text: #2c3e50 (dark gray)
Success: #4caf50 (green)
```

### 7. FILE NAMING CONVENTION
- Repository: `IEF_nonprofit-[calculator-name]`
- HTML file: `index.html`
- License: `LICENSE` (contains CC BY-NC-ND 4.0)

### 8. META TAGS (Include in <head>)
```html
<meta name="author" content="Alayna Weimer, IEF Fractional Services">
<meta name="copyright" content="© 2025 IEF Fractional Services">
<meta name="description" content="[Calculator description] - Part of the Nonprofit Toolkit Hub by IEF Fractional Services">
```

---

## ✅ VERIFICATION CHECKLIST

After creating calculator, verify:
- [ ] Copyright notice in HTML comment
- [ ] "Powered by IEF Fractional Services" in header
- [ ] Prominent license banner visible
- [ ] Footer with IEF branding
- [ ] Exports include branding
- [ ] Meta tags in head
- [ ] Color scheme matches IEF brand

---

## 📋 STANDARD CALCULATOR STRUCTURE

```
[Calculator Name]
├── Copyright notice (HTML comment)
├── Header with IEF branding
├── License banner (prominent)
├── Instructions/How it works
├── Calculator form/inputs
├── Results section
├── Download/Export buttons (with branded exports)
└── Footer with IEF branding
```

---

## 🎯 PROTECTION STRENGTH INDICATORS

**Minimum Protection (Required):**
- Copyright notice
- Header branding
- License banner
- Footer branding

**Enhanced Protection (Recommended):**
- All of above PLUS
- Branded exports/downloads
- Meta tags
- Multiple brand touchpoints
- Contact info in 3+ places

**Maximum Protection (Ideal):**
- All of above PLUS
- Unique visual elements tied to brand
- Custom graphics with watermarks
- API calls that require attribution
- Terms of use modal on first load

---

## 💬 SAMPLE PROMPT WITH PROTECTION LANGUAGE

Here's how to structure your request:

```
I need you to create a [CALCULATOR NAME] for my nonprofit toolkit platform.

[DESCRIBE CALCULATOR FUNCTIONALITY]

**DESIGN REQUIREMENTS:**
- Clean, modern, professional design
- Mobile responsive
- Use IEF brand color scheme:
  * Primary: #667eea (purple/blue)
  * Secondary: #764ba2 (purple)
  * Background: #f5f7fa (light gray)
  * Text: #2c3e50 (dark gray)

**TECHNICAL REQUIREMENTS:**
- Single HTML file (no external dependencies)
- All CSS in <style> tags
- All JavaScript in <script> tags
- Works when embedded in Squarespace Code Block

**BRAND PROTECTION REQUIREMENTS (CRITICAL):**
Include ALL of the following:

1. Copyright notice in HTML comment at top (see template)
2. "Powered by IEF Fractional Services" in header
3. Prominent CC BY-NC-ND 4.0 license banner
4. "Part of Nonprofit Toolkit Hub by Alayna Weimer" tagline
5. Footer with full IEF branding
6. Branded PDF/export content (if applicable)
7. Meta tags with copyright and author
8. Email: [your-email@example.com]

Follow the protection template exactly as specified.
```

---

## 🔧 EASY CUSTOMIZATION VARIABLES

For each new calculator, just update:
- `[CALCULATOR NAME]` - e.g., "Budget Estimator"
- `[Calculator Icon]` - e.g., 💰, 📊, 📝, 🎯
- `[Calculator tagline]` - e.g., "Calculate your nonprofit budget in minutes"
- `[your-email@example.com]` - Your actual email

Everything else stays the same!

---

## 📁 SAVE THIS FILE AS:

`_PROTECTION_TEMPLATE.txt`

Keep it accessible and copy-paste into every calculator request!
