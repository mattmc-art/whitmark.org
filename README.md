# whitmark.com, early 2000 (restored) v1.0

The last pre-SupplyOne version of whitmark.com, rebuilt from Internet Archive captures for hosting at whitmark.org.
Open `site/index.html`. It's fully self-contained, with no external requests. Rebuild with `cd src && python3 crawl.py && python3 build.py`.

**Which version this is.** The site is the "Whitmark Inc." FrontPage site as captured January to March 2000 ("founded in 1984 ... over 80 employees").
The site switched to a frames layout by June 2000. That version's pages (home.htm, employment.htm May 2000 and later) carry the "Whitmark Packaging, A SupplyOne Company" logo, so they're excluded.

**Changes from the original**
- Every page has an "Archived site" banner at the top and a v1.0 stamp in the footer.
- Employee captions and the contact list use first names only. The owners appear as "Mark and Chris".
- Suzanne Goldstein's tour photo and contact line are removed.
- These links are now plain text: mailto addresses, external links, the old-domain link, Search The Internet, Feedback Form, the Links in Tucson/Phoenix/Nogales pages (already 404 in 2000), the sales-order worksheet files, and the screen saver download (marked "no longer available").
- The hit counter and scripts are removed. Forms are disabled.
- employment.htm: the only pre-SupplyOne copy (Feb 1999) used the old button bar, so its text is set on the 2000 page template.
- products_and_services.htm: the only archived truck photo is the 2001 SupplyOne repaint, so it's replaced with the Whitmark Inc. logo.

**Not archived, so redrawn or substituted** (full list in `src/missing.log`)
- The corrugated backgrounds (fluteb.jpg, corrugat4e00.jpg) are redrawn kraft-flute textures.
- edgeofbd2.gif is replaced with edgeofbd.gif, the same artwork.
- The five section icons on Products & Services are redrawn as labeled tiles.
- Grey "Photo not archived" boxes stand in for:
  - Used Machinery: the three Titan drop sealer photos and the two Zed pressure former photos.
  - Tour photos 25, 84, 87 and 90 (Bob, Chris, Travis, and one production shot).
  - The full-size version of photo 89 (Nicole). Her thumbnail survives.
- Tour thumbnails 63 and 70 are regenerated from the full-size photos.
