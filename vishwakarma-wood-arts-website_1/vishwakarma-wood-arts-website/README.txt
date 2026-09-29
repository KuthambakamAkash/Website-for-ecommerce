Vishwakarma Wood Arts - Website Source
=========================================

WHAT'S INSIDE
-------------
index.html   - The complete website (HTML + CSS + JavaScript, all in one file).
               Product photos are embedded directly inside this file as base64
               data, so there are no separate image files to lose or misplace.

HOW TO USE IT
-------------
1. Just double-click index.html to preview it in any browser.
2. To publish it on the internet, upload index.html to any web host
   (examples: Hostinger, GoDaddy, Netlify, Vercel, GitHub Pages, or your
   own domain's hosting panel). Most hosts let you upload it as your
   homepage / index file.
3. No database, no server, no build step required - it is a static file.

THINGS YOU SHOULD EDIT BEFORE GOING LIVE
-----------------------------------------
Open index.html in any text editor (Notepad, VS Code, etc.) and update:

1. WhatsApp number
   Find this line near the top of the <script> section:
       const WA_NUMBER = "911234567890";
   Replace it with your real WhatsApp number in country-code format,
   digits only, no + or spaces (e.g. 919876543210 for a +91 98765 43210 number).

2. Business name
   Search for "Vishwakarma Wood Arts" (appears in the page title, header,
   footer and hero text) and replace with your actual store name.

3. Contact details
   In the <footer> section near the bottom of the file, update the phone
   number, email address, and working hours.

4. Prices
   Each product's price is set in the PRODUCTS list inside the <script>
   section (search for "price":). Update the numbers to your real pricing.

5. Product text / photos
   Each product also has "name", "desc", "wood", "finish", and "size"
   fields you can edit freely. To swap or add photos, they are stored as
   base64 image strings in the IMG object at the very top of the script -
   contact whoever manages the site for help re-generating this if you want
   to add brand-new photos later, since encoding a new image requires a
   quick conversion step.

HOSTING RECOMMENDATIONS (FREE / LOW COST)
------------------------------------------
- Netlify.com or Vercel.com: drag-and-drop index.html, get a live link in
  under a minute, free tier available.
- GitHub Pages: free hosting if you're comfortable with GitHub.
- Any Indian hosting provider (Hostinger, GoDaddy) if you want a custom
  domain like www.yourstorename.com.

Questions or want changes made for you (new products, real pricing, a
payment gateway, or admin panel to manage orders) - just ask.
