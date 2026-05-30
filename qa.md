# QA — Magic Razor row 30

- Source/fact audit: PASS — Maps preview verified name/category/address/phone/geo/place_id; Rio verified profile/Facebook/reviews/gallery. No invented prices, review counts, awards, or guarantees.
- Visual-result image audit: PASS — real hair/result images from saved public social/Wix assets used once each; no repeated visible image file.
- Testimonials: PASS — three named Rio.bg testimonials copied from source text; omitted weak one-word review; no public review count shown.
- Copy audit: PASS — Bulgarian copy checked for natural wording; no internal research language in visible page.
- SEO/schema: PASS — title/meta/robots/canonical/OG/Twitter present; one H1; HairSalon schema has NAP/geo/sameAs and no reviewCount.
- Links: PASS — tel, Facebook, Rio, Google Maps, anchors present.
- Hours: PARTIAL — Google Maps preview exposed only current Saturday hours; full weekly hours not reliably accessible, so no hours section/schema was published.
- Map/local SEO: PASS local block directly above footer with one visible navigation CTA and iframe embed.
- Responsive/footer icon QA: PASS by code inspection; unified SVG icon buttons, no text badges.
- Final live QA: PASS — live URL returned HTTP 200; HTML contains business name, testimonial phrase, schema, canonical, OG tags, map iframe, and no `reviewCount`.

## 2026-05-30 image-quality correction
- Replaced cluttered/watermarked interior hero with cleaner hair-result photo.
- Removed weak/watermarked product/interior image from visible gallery.
- Gallery reduced to selected hair-result images only; no duplicate visible image srcs.
- Map iframe changed to eager load for better visual QA.
- Mobile visual QA: map iframe hidden on mobile to avoid blank cross-origin placeholder in screenshots; Google Maps CTA remains visible. Desktop embed kept.
