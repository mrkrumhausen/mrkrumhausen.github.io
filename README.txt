skrumhausen.com SEO update: how to install

1. Copy these 4 files into the ROOT of the mrkrumhausen.github.io repo:
   index.html (replaces the old one)
   interim-fractional-cpo-copenhagen.html (new)
   sitemap.xml (replaces the old one)
   robots.txt (new)

2. Search all files for BOOKING_LINK_HERE and replace it with your booking URL.
   Search for "TODO Sebastian" and fill or delete each comment.
   Do not publish before the track-record TODO is done.

3. Also fix principles.md and principles.html: the "Back to home" link points
   to krumhausen.com (dead). Change it to https://skrumhausen.com.

4. Commit and push to master. GitHub Pages deploys in a minute or two.

5. After it is live:
   - Add https://skrumhausen.com in Google Search Console and submit sitemap.xml
   - Set your LinkedIn headline to match: Interim and Fractional CPO, Copenhagen
   - Check that /interim-fractional-cpo-copenhagen loads (no .html needed)
