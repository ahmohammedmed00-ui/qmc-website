QMC website v41 - ready to deploy
Upload: firebase deploy --only hosting  (or upload the whole folder as is)
Background video: videos/qmc-bg.mp4 (+ poster images/qmc-bg-poster.webp). Replace both files to change it.
Optional before launch: add og:image (absolute URL) and canonical link once the domain is known.

v38: steel works section redesigned (spotlight viewer + filmstrip, category counts, WhatsApp 'similar work' button, autoplay with pause, swipe/keyboard). Edit the P array in index.html (search 'steel showroom v4') to add or reorder photos.
v39: steel works section is now a flowing justified gallery (71 photos, no category filters, 'show more' button). To add photos, edit the P array in index.html (search 'steel showroom v5'): [image, arabic caption, english caption, width/height ratio].
v40: local SEO (LocalBusiness schema, canonical, og tags, image alt text, sitemap.xml, robots.txt), shorter intro (2.8s), steel gallery trimmed to 40 photos shown all at once.
v41: steel works = 3D page-flip catalogue (swipe/drag, arrows, ruler, autoplay). Fixed duplicate element IDs that left project titles/descriptions empty and the gallery counter stuck. Location: live Google Maps embed + links to the factory listing. Footer: contact, address, quick links. ImageGallery JSON-LD added.
v42: kitchen designer: +37 products (cold & hot units, steel works parts: railings, stairs, canopy, bollards, lockers...), category filter, 3 ready templates, 9D mode (3D + 6 data layers: material, weight, power, utilities, lead time, work zones) with auto tour and smart design checks; 9D totals added to the WhatsApp message. Product data (kW, days) lives in the X table in index.html (search "9D layers").
