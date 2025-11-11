# 🎯 Nonprofit Mission Statement Generator

A beautiful, interactive tool that helps nonprofit leaders create professional mission statements through guided questions. Watch your mission statement build in real-time as you type!

![Mission Statement Generator](https://img.shields.io/badge/status-ready-success)
![HTML](https://img.shields.io/badge/HTML-5-orange)
![CSS](https://img.shields.io/badge/CSS-3-blue)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow)

## ✨ Features

- **Real-time Generation** - Mission statement updates as you type
- **Guided Questions** - 6 thoughtful questions (4 required, 2 optional)
- **Beautiful Design** - Modern, professional interface with smooth animations
- **Mobile Responsive** - Works perfectly on all devices
- **Copy to Clipboard** - One-click copying of your mission statement
- **Download as PDF** - Export your statement as a printable HTML file
- **Inspiring Examples** - Real mission statements from leading nonprofits
- **No Dependencies** - Pure HTML, CSS, and JavaScript (no libraries needed)

## 🚀 Quick Start

### Option 1: Use Directly from GitHub Pages

Simply visit the live demo: `https://YOUR-USERNAME.github.io/nonprofit-mission-generator/`

### Option 2: Download and Use Locally

1. Download `index.html`
2. Open it in any web browser
3. Start creating your mission statement!

### Option 3: Embed in Your Website

Copy the contents of `index.html` and paste into your website's code block or HTML editor.

## 📦 Embedding in Squarespace

1. Go to your Squarespace page editor
2. Add a **Code Block**
3. Copy the entire contents of `index.html`
4. Paste into the code block
5. Save and publish!

**Pro Tip:** For best results in Squarespace, use a full-width section.

## 🎨 Design

- **Color Scheme:**
  - Primary: `#667eea` (Purple/Blue)
  - Secondary: `#764ba2` (Purple)
  - Background: `#f5f7fa` (Light Gray)
  - Text: `#2c3e50` (Dark Gray)

- **Typography:** System fonts for optimal performance
- **Layout:** Centered, max-width 900px for readability
- **Animations:** Smooth fade-in transitions

## 📝 How It Works

Users answer 6 guided questions:

1. **What problem does your organization solve?** (Required)
2. **Who do you serve?** (Required)
3. **How do you serve them?** (Required)
4. **What is the ultimate outcome or impact?** (Required)
5. **What makes your approach unique?** (Optional)
6. **What are your core values?** (Optional)

The tool intelligently combines their answers into a professional mission statement that follows nonprofit best practices.

## 🛠️ Customization

### Changing Colors

Edit the CSS variables in the `<style>` section:

```css
/* Primary gradient */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);

/* Adjust to your brand colors */
background: linear-gradient(135deg, #YOUR_COLOR_1 0%, #YOUR_COLOR_2 100%);
```

### Modifying Questions

Edit the question labels and placeholders in the HTML:

```html
<label class="question-label">
    <span class="question-number">1</span>
    Your Custom Question Here
</label>
<input 
    type="text" 
    id="problem" 
    placeholder="Your custom placeholder..."
>
```

### Adjusting the Statement Logic

The mission statement generation logic is in the `updateMissionStatement()` function. Customize how answers are combined by editing this JavaScript function.

## 🌟 Examples

The tool includes inspiring examples from:
- **Habitat for Humanity**
- **American Red Cross**
- **Feeding America**

## 📱 Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 License

This work is licensed under the **Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License**.

![License: CC BY-NC-ND 4.0](https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey.svg)

**For nonprofits:** Free to use  
**For personal use:** Free to use  
**For commercial use:** Contact for licensing

This means:
- ✅ Nonprofits can use this tool freely
- ✅ Individuals can use for personal purposes
- ❌ Cannot be used in commercial products/services
- ❌ Cannot be modified or adapted
- ❌ Cannot be used by competing toolkit/consulting businesses

For commercial licensing inquiries, contact: [your email]

See [LICENSE](LICENSE) for full terms.

---

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests
- Improve documentation

## 📄 License

MIT License - Feel free to use this tool for your nonprofit toolkit platform!

## 🎯 Use Cases

Perfect for:
- Nonprofit startup founders
- Board retreats and strategic planning
- Grant applications
- Website content
- Marketing materials
- Annual reports

## 💡 Tips for Best Results

1. **Be specific** - Avoid vague language
2. **Focus on impact** - Emphasize outcomes, not just activities
3. **Keep it concise** - Aim for 1-2 sentences
4. **Make it memorable** - Use clear, powerful language
5. **Test it out** - Share with your team for feedback

## 🔗 Related Tools

Part of the **Nonprofit Toolkit Hub** - a comprehensive platform providing essential resources for nonprofit leaders.

## 📧 Support

For questions or support, please open an issue on GitHub.

---

Made with ❤️ for nonprofit leaders everywhere
