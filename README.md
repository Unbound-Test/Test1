# Unbound Concierge Services - Coming Soon Website

## Files Included:
- index.html (Landing page with "Get In Touch" button)
- contact.html (Contact form page)
- styles.css (All styling)
- logo.png (Your master logo with true black background)
- README.md (This file - setup instructions)

## Setup Instructions:

### Step 1: Upload to GitHub

1. Go to https://github.com/[your-username]/Unbound1
2. Click "Add file" → "Upload files"
3. Drag and drop ALL FIVE files:
   - index.html
   - contact.html
   - styles.css
   - logo.png
   - README.md (optional - just for your reference)
4. Scroll down, add commit message: "Initial website upload"
5. Click "Commit changes"

### Step 2: Enable GitHub Pages (if not done already)

1. In your repository, click "Settings" (top menu)
2. Click "Pages" in left sidebar
3. Under "Build and deployment":
   - Source: "Deploy from a branch"
   - Branch: "main"
   - Folder: "/ (root)"
4. Click "Save"

### Step 3: Wait 2-3 Minutes

GitHub will build and deploy your site. Your site will be live at:
https://[your-username].github.io/Unbound1/

### Step 4: Set Up Formspree (Contact Form)

1. Go to https://formspree.io
2. Sign up for free account (using hello@unboundconcierge.co.uk)
3. Create new form
4. Copy your form ID (looks like: xyzabc123)
5. Edit contact.html in GitHub:
   - Click on contact.html
   - Click pencil icon (Edit)
   - Find line: action="https://formspree.io/f/YOUR_FORM_ID"
   - Replace YOUR_FORM_ID with your actual ID
   - Commit changes

Now form submissions will go to hello@unboundconcierge.co.uk!

### Step 5: Connect Custom Domain (When You Buy unboundconcierge.co.uk)

**In GitHub:**
1. Go to Settings → Pages
2. Under "Custom domain", enter: unboundconcierge.co.uk
3. Click Save
4. Wait for DNS check

**In GoDaddy:**
1. Go to DNS Management for unboundconcierge.co.uk
2. Add these records:

   A Records (all pointing to GitHub):
   - @ → 185.199.108.153
   - @ → 185.199.109.153
   - @ → 185.199.110.153
   - @ → 185.199.111.153

   CNAME Record:
   - www → [your-username].github.io

3. Wait 24-48 hours for DNS to propagate
4. Your site will be live at https://unboundconcierge.co.uk

GitHub will automatically generate FREE SSL certificate (HTTPS).

## Design Details:

**Colors:**
- Background: #000000 (pure black - makes logo float beautifully)
- Text: White (#FFFFFF)
- Accent/Buttons: #4A90E2 (professional blue)
- Button Hover: #5BA3F5 (lighter blue)

**Features:**
- Fully responsive (mobile, tablet, desktop)
- Large, impossible-to-miss buttons
- Clean, understated design matching your logo
- Professional blue accent color
- Contact form sends to hello@unboundconcierge.co.uk
- Company field for B2B contacts

**Messaging:**
- "Coming Soon" (not "Launching Soon")
- Tagline: "We Coordinate, Validate & Advocate"
- Description: "Expert lifestyle coordination for busy professionals"

## Need Help?

If anything doesn't work or you want to make changes, just ask!

---

**Current Status:** Ready to upload to GitHub!
