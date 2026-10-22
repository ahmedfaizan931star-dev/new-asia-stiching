New Asia Stitching Studio website

Upload every file in this folder to the ROOT of your repo/Vercel project (index.html, ladies-tailor-chakwal.html, gents-tailor-chakwal.html, slip.html, robots.txt, sitemap.xml, icons and all .webp images together), then commit/redeploy.
To change a photo, replace the .webp file with the same name.
Prices: open index.html and search for "from Rs" to edit them. Prices also appear inside the JSON-LD block near the top and in the FAQ - keep them the same.

SEO notes
- Site URL used everywhere: https://new-asia-stitching.vercel.app/
  If you buy a domain later, search-replace that URL in index.html, robots.txt and sitemap.xml.
- slip.html is the shop's private order-slip page (noindex). Open /slip.html on the shop phone and "Add to Home screen".

Search engine setup (free)
1. Google Search Console: add https://new-asia-stitching.vercel.app/ as a URL-prefix property. Choose the HTML tag method and paste the <meta name="google-site-verification" ...> tag in the <head> of index.html (replace the comment "Search Console / Bing verification tags go here"). Redeploy, click Verify, then submit sitemap.xml.
2. Bing Webmaster Tools: sign in and use "Import from Google Search Console" (no extra verification), or add the site and paste the <meta name="msvalidate.01" ...> tag the same way.
3. Google Business Profile and Bing Places: claim the shop, add the website link, photos, timings and phone exactly as on the site.
Keep the shop name, address and phone identical everywhere.
