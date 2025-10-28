Swap Top Hats — Coming Soon

Files
-----
/index.html
/assets/favicon.svg
/assets/apple-touch-icon.png
/assets/og-image.png

Quick Deploy (GitHub Pages)
--------------------------
1) Create a new PUBLIC repo on GitHub (e.g., swaptophats).
2) Click "Add file" -> "Upload files" and upload everything in this ZIP, preserving folders.
3) Repo Settings -> Pages -> Build and deployment:
   Source: Deploy from a branch
   Branch: main   Folder: /(root)
   Save.
4) Your site will appear at https://<your-username>.github.io/swaptophats

Connect Your Domain (Namecheap -> GitHub Pages)
-----------------------------------------------
In Namecheap -> Domain List -> Manage -> Advanced DNS:
1) CNAME record
   Type: CNAME   Host: www   Value: <your-username>.github.io   TTL: Automatic
2) A records (optional, makes the bare domain work too)
   Type: A  Host: @  Value: 185.199.108.153
   Type: A  Host: @  Value: 185.199.109.153
   Type: A  Host: @  Value: 185.199.110.153
   Type: A  Host: @  Value: 185.199.111.153

(Then, in GitHub repo -> Settings -> Pages -> Add your custom domain and enforce HTTPS.)

Email Capture
------------
The current form uses mailto: which opens an email to sales@swaptophats.com.
Swap this for Formspree or Shopify for real email collection when you're ready.
