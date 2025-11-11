# 🔒 Licensing Guide: Choose Your Protection Level

## Your License Options

I've created **3 different licenses** for you to choose from. Each offers different levels of protection.

---

## 📊 Quick Comparison

| License | Protection Level | Commercial Use? | Modifications? | Best For |
|---------|-----------------|-----------------|----------------|----------|
| **MIT** (current) | ⭐ Low | ✅ Yes | ✅ Yes | Maximum sharing |
| **CC BY-NC-ND** | ⭐⭐⭐ High | ❌ No | ❌ No | Public but protected |
| **Proprietary** | ⭐⭐⭐⭐⭐ Maximum | ❌ No* | ❌ No | Full control |

*Proprietary allows commercial use only with paid license

---

## Option 1: Keep MIT License (Current)

**File:** `LICENSE` (already in your project)

### ✅ Pros:
- Maximum visibility and sharing
- Builds trust and credibility
- Can become popular (more stars/forks)
- Attracts potential clients
- Shows generosity

### ❌ Cons:
- Anyone can copy and use commercially
- Competitors can use in their toolkits
- Can modify without telling you
- Only requires attribution (often ignored)

### 🎯 Use This If:
- You want maximum reach
- You see it as pure marketing
- You're okay with others using it
- Your value is consulting, not the tool

---

## Option 2: Creative Commons BY-NC-ND ⭐ RECOMMENDED

**File:** `LICENSE-CC-BY-NC-ND`

### ✅ Pros:
- **Prevents commercial use** (no competing toolkits)
- **Prevents modifications** (can't rebrand/resell)
- Still allows nonprofit use
- Maintains public visibility
- Can still use GitHub Pages
- Shows you're protecting your IP
- Can sell commercial licenses separately

### ❌ Cons:
- May seem less "generous"
- Requires enforcement (you must monitor)
- Some people may not understand the license

### 🎯 Use This If:
- You want to stay public BUT protected
- You want to prevent competitors from using it
- You're willing to enforce your rights
- You may want to sell commercial licenses later

### 💰 Revenue Opportunity:
You can charge others for commercial use:
- Consulting firms: $500-2,000/year
- SaaS platforms: $2,000-5,000/year
- White-label rights: $5,000-10,000/year

---

## Option 3: Proprietary License (Maximum Protection)

**File:** `LICENSE-PROPRIETARY`

### ✅ Pros:
- **Complete control** over all use
- Clear legal standing
- Explicitly lists prohibited uses
- Includes commercial licensing terms
- Professional and serious tone
- Easy to enforce

### ❌ Cons:
- Should make repository **private** (or it looks contradictory)
- Less discoverable
- May hurt your "helpful consultant" brand
- No GitHub Pages (unless private)
- Seems less generous

### 🎯 Use This If:
- You want absolute maximum protection
- You plan to sell the tool as part of paid tiers
- You're worried about direct competitors
- You want to license commercially

---

## 🎨 My Strategic Recommendation

### **Use Creative Commons BY-NC-ND** (Option 2)

**Why?**
1. ✅ Stays public (builds credibility)
2. ✅ Prevents commercial abuse
3. ✅ Allows nonprofit free use
4. ✅ Maintains GitHub Pages
5. ✅ Opens commercial licensing revenue
6. ✅ Shows you're professional about IP

### **Strategy:**
- **Free for nonprofits** → Builds goodwill
- **Free personal use** → Marketing reach  
- **Paid for competitors** → Revenue stream
- **Your brand embedded** → Lead generation

---

## 📝 Implementation Steps

### **To Switch to CC BY-NC-ND:**

1. **Replace the license file:**
   ```bash
   cd nonprofit-mission-generator
   rm LICENSE
   cp LICENSE-CC-BY-NC-ND LICENSE
   ```

2. **Update README.md:**
   Change the license section to:
   ```markdown
   ## 📄 License
   
   This work is licensed under the Creative Commons 
   Attribution-NonCommercial-NoDerivatives 4.0 International License.
   
   **For nonprofits:** Free to use
   **For commercial use:** Contact [your email] for licensing
   
   See [LICENSE](LICENSE) for full terms.
   ```

3. **Add license badge to README:**
   ```markdown
   ![License: CC BY-NC-ND 4.0](https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey.svg)
   ```

4. **Add to the calculator itself:**
   In `index.html`, add after the header:
   ```html
   <div style="text-align: center; padding: 10px; font-size: 0.85em; color: #666; background: #f9f9f9;">
       © 2025 IEF Fractional Services | 
       <a href="https://creativecommons.org/licenses/by-nc-nd/4.0/" style="color: #667eea;">
           CC BY-NC-ND 4.0
       </a> | 
       <a href="mailto:your@email.com" style="color: #667eea;">
           Commercial License Available
       </a>
   </div>
   ```

5. **Commit and push:**
   ```bash
   git add LICENSE README.md index.html
   git commit -m "Update to CC BY-NC-ND 4.0 license"
   git push
   ```

---

### **To Switch to Proprietary:**

1. **Make repository private** (in GitHub Settings)

2. **Replace the license file:**
   ```bash
   cd nonprofit-mission-generator
   rm LICENSE
   cp LICENSE-PROPRIETARY LICENSE
   ```

3. **Update README.md:**
   ```markdown
   ## 📄 License
   
   Proprietary and Confidential.
   © 2025 Alayna Weimer / IEF Fractional Services. All Rights Reserved.
   
   For licensing inquiries, contact: [your email]
   ```

4. **Disable GitHub Pages** (won't work with private repo anyway)

5. **Deploy to Squarespace only**

---

## ⚖️ Legal Enforcement

### **If Someone Violates Your License:**

1. **Document the violation**
   - Screenshot their use
   - Save URLs and dates
   - Document any commercial use

2. **Send a cease and desist**
   - Email template provided below
   - Professional but firm
   - Give them options (remove or license)

3. **Offer a license**
   - Turn violation into revenue
   - "Pay $X for retroactive license"

4. **DMCA takedown** (if hosted)
   - GitHub respects DMCA
   - Can force removal

5. **Legal action** (last resort)
   - Usually not worth it for small tools
   - Use as leverage only

---

## 📧 Cease and Desist Email Template

```
Subject: Unauthorized Use of Proprietary Software

Dear [Name/Company],

I am writing regarding your use of the Mission Statement Generator 
tool originally created by IEF Fractional Services and available at 
[your GitHub URL].

This software is licensed under [CC BY-NC-ND 4.0 / Proprietary License], 
which prohibits commercial use without authorization. Your current use at 
[their URL/product] appears to violate these terms.

I am happy to discuss a commercial licensing agreement that would allow 
you to continue using this tool legally. Alternatively, I must request 
that you immediately cease use and remove the tool from your platform.

Please respond within 7 business days to discuss a resolution.

Best regards,
Alayna Weimer
IEF Fractional Services
[your contact info]
```

---

## 💡 Pro Tips

1. **Monitor usage:** Set up Google Alerts for phrases from your tool
2. **Watermark visibly:** Make your branding hard to remove
3. **Link back:** Embed links that drive traffic to you
4. **Track it:** Use analytics (if self-hosted) to see who uses it
5. **License it:** Turn violations into revenue opportunities

---

## 🎯 Final Decision Matrix

**Choose MIT if:**
- Maximum reach is priority
- It's pure marketing
- You don't care about protection

**Choose CC BY-NC-ND if:** ⭐ **RECOMMENDED**
- You want public but protected
- You want to prevent commercial abuse
- You want licensing revenue potential
- You want to help nonprofits freely

**Choose Proprietary if:**
- You need maximum control
- You'll make it private
- You're selling access
- You have competing concerns

---

## ✅ Ready to Decide?

**My recommendation:** Start with **CC BY-NC-ND**, and here's why:

1. Nonprofits can use it freely (builds goodwill)
2. Competitors must pay (protects you)
3. Stays public (builds credibility)
4. Easy to upgrade to Proprietary later if needed
5. Opens commercial licensing revenue stream

**Want me to implement CC BY-NC-ND for you?** Just let me know!
