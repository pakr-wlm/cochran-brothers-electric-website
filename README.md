# Cochran Brothers Electric Co., Inc. (Gainesville, GA): Website

Test build of the electrician-website-generator skill from a bare URL (cochranbrotherselectric.com).

Old site: a 2000s-style Network Solutions page. The hero area renders blank, the request form on the Press Releases page shows
"Invalid Form properties detected", no reviews or testimonials appear anywhere, no license number, two different emails on the home page,
and the copyright says 2021. That is the outreach angle: real reviews (5.0 on Google) exist but are not on the site.

Edit `index.src.html` / `styles.css`, run `python build.py`.

## Real data used (source)
- Name, tagline "Energy Under Control", phone (770) 534-2584, address 2334 Centennial Circle, Gainesville, GA 30504, hours Mon-Fri 7-5, 24/7 emergency service, 60-mile service radius: their site (About, Services, History, Contact pages); address/phone/site also match the Google Maps profile
- Service lists (residential, commercial, industrial), staff credentials (certified infrared thermographer, AutoCAD certified, PLC technicians), "never sell you more service than you need", drug-free screening, founders James and Stanley Cochran, Stanley directs the company: their About/Services/History pages
- Email kcochran@cochranbrotherselectric.com (used for the quote form): About, Services, History pages
- Google rating 5.0 from 7 ratings, and two verbatim reviews (Gerald Driver, Amanda Lewis): Google Maps place page for Cochran Brothers Electric Co., Inc.
- Photos from their site: crew and truck (hero), technicians at a counter (About), two technicians testing a control device (gallery tile 1), Greater Hall Chamber "Certified Small Business Partner" badge, logo. Colors sampled from the logo (red 232,0,0 and black). The logo's gray gradient background was removed (transparent PNG; white-ink copy over the hero photo, black-ink copy on the scrolled header)

## Still placeholders / stock
- Gallery tiles 2-4 are Pexels stock (commercial ceiling conduit, generator, panel diagnosis), credited in HTML comments; replace with real job photos first
- Hero photo is only 1000px wide (their file); a larger original would sharpen it
- Their photos may not all be job photos (the counter shot is a group at a reception desk)

## Conflicts to confirm
- Years: home and History pages say "more than 42 years", About says 43 years of experience, copyright is 2021. No years figure is shown
- Email: home page lists kaycochran@bellsouth.net, other pages kcochran@cochranbrotherselectric.com. Form uses the second; confirm which inbox is read
- Owner name: About says Stanley Cochran directs the company; a search summary named "Kay Cochran" as the email contact
- Hours: their site says 7-5; an aggregator summary said 4:30 PM close. Site hours used
- Facebook page is titled "Cochran Brothers Electric Co., Inc." at /GainesvilleElectrical; separate from the Google profile

## Not used (and why)
- Facebook review from "Joyce Cochran Jenkins" (shares the owners' surname, possibly a relative); Facebook "recommends" from Curtis Collins and Jw Thrash have no text
- Google "AI overview" rating summary (it cited Yelp and Facebook, not Google reviews)
- Birdeye (9 reviews, 5.0): page blocks bots, no text retrieved. Indeed page (employee reviews) ignored
- Portrait photo of an unidentified man in a blazer on their About page: no name on the site, so not captioned or used
- April newsletter scan (Greater Hall Chamber Business Link): a document, not a photo
- Founder's Agent Orange story from the History page: personal, left to the owner to decide
- Google reviews are about 5 years old and only 2 of the 7 ratings have text: ask the owner for fresh Google reviews

## Next steps for the owner
- Fresh Google reviews (ask the last 5-10 customers)
- Real job photos and a sharper crew photo
- License number, founding year, named towns served
- After launch (need a live domain): run seo-page, seo-technical, seo-audit and seo-google; add canonical and og:image

## Google reviews report (google-report.html)
Standalone outreach page for Kay Cochran: Cochran Brothers (5.0, 7 Google reviews) vs Argo Total Electrical (4.9, 208), why reviews drive local ranking, a job-value calculator and a 90-day plan. Not linked from the homepage and marked noindex. Numbers live in the `DATA` block at the bottom of the file.
