================================================================================
                    MODENGINE2 WEBSITE - README
================================================================================

🎮 Welcome to the ModEngine2 Website!

This is a professional, modern, and fully responsive multi-page website built 
with HTML, CSS, and JavaScript. It's designed to showcase ModEngine2 with a 
clean, elegant interface that works perfectly on all devices.

================================================================================
                           FILE STRUCTURE
================================================================================

modengine2-website/
│
├── index.html          (Home page with hero section and focus keywords)
├── about.html          (About page with mission and vision)
├── contact.html        (Contact page with Google Form button)
├── download.html       (Download page with download button)
├── style.css           (All styling and responsive design)
├── script.js           (JavaScript for interactivity)
└── README.txt          (This file - setup and customization guide)

================================================================================
                       HOW TO RUN THE WEBSITE
================================================================================

METHOD 1: Direct Opening (Simplest)
------------------------------------
1. Navigate to the folder containing these files
2. Double-click on "index.html"
3. The website will open in your default web browser

METHOD 2: Local Server (Recommended for Development)
-----------------------------------------------------
If you have Python installed:
1. Open command prompt/terminal in the website folder
2. Run: python -m http.server 8000
3. Open browser and go to: http://localhost:8000

If you have Node.js with Live Server:
1. Install Live Server: npm install -g live-server
2. Navigate to the website folder
3. Run: live-server
4. The website will open automatically

METHOD 3: Using VS Code Live Server
------------------------------------
1. Open the folder in Visual Studio Code
2. Install "Live Server" extension
3. Right-click on index.html
4. Select "Open with Live Server"

================================================================================
                      HOW TO CUSTOMIZE THE WEBSITE
================================================================================

📌 CHANGING COLORS
------------------
Open "style.css" and find the ":root" section (around line 11):

--primary-color: #C46C11;      (Main orange color - change this)
--secondary-color: #FFFFFF;    (White - background color)
--accent-color: #C46C11;       (Accent color - usually same as primary)
--text-color: #000000;         (Main text color - black)

Simply replace these hex color codes with your desired colors.

Example Color Schemes:
- Blue Theme: #2563EB (primary), #FFFFFF, #2563EB, #000000
- Purple Theme: #7C3AED (primary), #FFFFFF, #7C3AED, #000000
- Green Theme: #059669 (primary), #FFFFFF, #059669, #000000

📌 CHANGING LINKS
-----------------

Google Form Link (Contact Page):
1. Open "contact.html"
2. Find line with: https://docs.google.com/forms/d/e/1FAIpQLSf...
3. Replace with your Google Form link

GitHub Repository Link (Navigation & Footer):
1. Search for: https://github.com/open-ssh/ModEngine2
2. Replace all instances with your GitHub repository URL
   (Appears in all HTML files)

Download Link (Download Page):
1. Open "download.html"
2. Find: https://modengine2.com/download/
3. Replace with your actual download link

Official Site Link (Home Page):
1. Open "index.html"
2. Find: https://modengine2.com/
3. Replace with your official website URL

📌 CHANGING KEYWORDS & SEO LINKS
---------------------------------

The home page (index.html) contains three focus keyword links:

1. "mod engine" → https://modengine2.com/
2. "how to use mod engine 2 elden ring cracked" → 
   https://modengine2.com/how-to-launch-elden-ring-with-mod-engine-2/
3. "mod engine 2 seamless coop" → 
   https://modengine2.com/how-to-use-seamless-co-op-with-mod-engine-2/

To change these:
1. Open "index.html"
2. Search for the keyword text
3. Update both the anchor text and href attribute with your new keywords/URLs

📌 CHANGING TEXT CONTENT
-------------------------

Each HTML file contains text content that you can easily modify:

- index.html: Hero section, features, content sections
- about.html: Mission, vision, values, timeline
- contact.html: Introduction text, FAQ items
- download.html: Download description, installation steps

Simply open the file and edit the text between HTML tags:
<p>Your text here</p>
<h2>Your heading here</h2>

📌 CHANGING FONTS
-----------------

Current fonts used:
- Headings: 'Poppins'
- Body text: 'Inter'

To change fonts:
1. Visit Google Fonts: https://fonts.google.com/
2. Select your preferred fonts
3. Copy the <link> code
4. Replace the existing Google Fonts link in each HTML file
5. Update font-family in style.css (search for 'Poppins' and 'Inter')

📌 CHANGING IMAGES/ICONS
-------------------------

The current website uses:
- SVG icons (built into the HTML)
- Emoji icons (🚀, 🎮, etc.)

To add custom images:
1. Create an "images" folder in the website directory
2. Place your images in this folder
3. In HTML, add: <img src="images/your-image.jpg" alt="Description">

📌 MODIFYING NAVIGATION MENU
-----------------------------

To add/remove menu items:
1. Open any HTML file
2. Find the <nav> section
3. Add or remove <li> items in the <ul class="nav-menu">

Example:
<li><a href="newpage.html" class="nav-link">New Page</a></li>

📌 CHANGING FOOTER
------------------

To update footer content:
1. Open any HTML file
2. Scroll to the <footer> section
3. Edit:
   - Copyright year: &copy; 2024
   - Company name: ModEngine2
   - Footer credit: "Designed & Developed by..."
   - Social links: Update href attributes

================================================================================
                          RESPONSIVE DESIGN
================================================================================

The website is fully responsive and works on:
- Desktop (1920px and above)
- Laptop (1024px - 1920px)
- Tablet (768px - 1024px)
- Mobile (320px - 768px)

Breakpoints are defined in style.css:
- @media (max-width: 768px) - Tablet and mobile
- @media (max-width: 480px) - Small mobile devices

To adjust responsive behavior, modify these sections in style.css.

================================================================================
                       JAVASCRIPT FEATURES
================================================================================

The script.js file includes:
✓ Mobile navigation toggle with hamburger animation
✓ Smooth scrolling for anchor links
✓ Header shadow effect on scroll
✓ Intersection Observer for fade-in animations
✓ Active navigation link highlighting
✓ Scroll to top button
✓ Loading animation

To disable any feature:
1. Open script.js
2. Comment out or remove the corresponding section

================================================================================
                       BROWSER COMPATIBILITY
================================================================================

The website works on:
✓ Chrome (Latest)
✓ Firefox (Latest)
✓ Safari (Latest)
✓ Edge (Latest)
✓ Opera (Latest)

For older browsers (IE11), some modern CSS features may not work.

================================================================================
                          SEO OPTIMIZATION
================================================================================

Each page includes:
- Meta description
- Meta keywords
- Semantic HTML5 tags (header, nav, main, section, footer)
- Proper heading hierarchy (h1, h2, h3)
- Alt attributes for images (when you add them)
- Internal linking between pages
- Focus keywords naturally integrated in content

To improve SEO:
1. Add more relevant content to each page
2. Include alt text for all images
3. Add Open Graph meta tags for social sharing
4. Submit sitemap to Google Search Console

================================================================================
                        DEPLOYMENT OPTIONS
================================================================================

OPTION 1: GitHub Pages (Free)
------------------------------
1. Create a GitHub repository
2. Upload all website files
3. Go to repository Settings > Pages
4. Select main branch as source
5. Your site will be live at: username.github.io/repository-name

OPTION 2: Netlify (Free)
-------------------------
1. Create account at netlify.com
2. Drag and drop your website folder
3. Get instant deployment with HTTPS
4. Optional: Connect custom domain

OPTION 3: Vercel (Free)
------------------------
1. Create account at vercel.com
2. Import your project
3. Deploy with one click
4. Automatic HTTPS and CDN

OPTION 4: Traditional Web Hosting
----------------------------------
1. Choose a hosting provider (Hostinger, Bluehost, etc.)
2. Upload files via FTP
3. Point your domain to the hosting
4. Website goes live

================================================================================
                           TROUBLESHOOTING
================================================================================

PROBLEM: Navigation menu doesn't work on mobile
SOLUTION: Make sure script.js is properly linked in all HTML files

PROBLEM: Styles not loading
SOLUTION: Check that style.css is in the same folder as HTML files

PROBLEM: Google Form button not working
SOLUTION: Verify the Google Form link in contact.html

PROBLEM: Links opening in same tab
SOLUTION: Add target="_blank" to external links

PROBLEM: Fonts not loading
SOLUTION: Check internet connection (Google Fonts requires internet)

================================================================================
                          PERFORMANCE TIPS
================================================================================

To optimize performance:
1. Minimize CSS and JavaScript files (use online minifiers)
2. Compress images before adding them
3. Use WebP format for images
4. Enable browser caching on your server
5. Use a CDN for faster global delivery

================================================================================
                           SUPPORT & HELP
================================================================================

For issues or questions:
1. Check this README file thoroughly
2. Review the code comments in HTML, CSS, and JS files
3. Search for similar issues online
4. Consult web development forums (Stack Overflow, etc.)

================================================================================
                           LICENSE & CREDITS
================================================================================

Website Design: Professional Web Solutions
Color Palette: #C46C11 (Orange), #FFFFFF (White), #000000 (Black)
Fonts: Google Fonts (Inter, Poppins)
Icons: SVG icons and emoji characters

This website is created for ModEngine2 project.
Feel free to modify and customize according to your needs.

================================================================================
                         VERSION INFORMATION
================================================================================

Website Version: 1.0
Creation Date: 2024
Last Updated: 2024

Features:
✓ 4 Pages (Home, About, Contact, Download)
✓ Fully Responsive Design
✓ Mobile Navigation
✓ Smooth Animations
✓ SEO Optimized
✓ Modern UI/UX
✓ Clean Code Structure

================================================================================

Thank you for using this website template!
For best results, customize the content to match your brand and needs.

🎮 Happy modding with ModEngine2!

================================================================================
