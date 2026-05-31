# Image map — Фризьорски салон Magic Razor (row 30)

## Sources checked
- Google Maps preview by place_id `ChIJM17w2MOFqkARXiLdnJpAAGA`: verified name, category, address, phone, geo, rating; only limited photo/review text exposed in fetched preview.
- Rio.bg profile `https://rio.bg/places/sofia/beauty-salon-magic-razor`: verified public profile, Facebook link, salon description, massage offers, five named Rio reviews, gallery URLs.
- Facebook direct page `https://www.facebook.com/MgcRzr/` and mobile variant: public page resolves; assets previously saved from public FB/Wix/CDN routes in this folder.
- Search routes attempted: Brave API returned quota 402; Google web search returned 429; Bing and DuckDuckGo returned irrelevant/generic results for Cveti/Contessa style queries but Rio page resolved directly for Magic Razor.

## May 31 image correction
Dean flagged the published images as terrible-looking. The issue was real: the page was using several 206×206 thumbnail assets as hero/gallery images, so they looked soft and cheap when enlarged. I removed those from visible placements and switched to the strongest higher-resolution public/Wix assets already saved in the project.

## Selected images
| file | source | subject | class | scores | placement | notes |
|---|---|---|---|---|---|---|
| `assets/magic-wix-5.jpg` | saved public Wix asset | long styled hair / salon glamour image | hero candidate | realness 3, sharpness 5, crop 5, fit 5, relevance 5, uniqueness 4 | hero + OG/schema image | high-impact and much cleaner than the old 206px hero; crop-safe portrait |
| `assets/magic-fb-2.jpg` | saved public Facebook asset | colorful hair / creative styling graphic | service/action | 4/4/4/5/5/5 | gallery feature | strongest branded/creative image; used large, not repeated |
| `assets/magic-wix-3.jpg` | saved public Wix asset | braided/colored hairstyle | service/action | 4/4/4/4/5/5 | gallery | salon-relevant and clearer than thumbnail result images |
| `assets/magic-wix-6.jpg` | saved public Wix asset | updo/formal hairstyle close-up | service/action | 3/4/3/4/5/4 | gallery portrait | tall source; CSS keeps mobile natural and desktop crop controlled |
| `assets/salon-interior.webp` | prior saved public social/Rio asset | interior / barber stations | room/interior | 4/4/4/5/4/5 | gallery support | real location proof; lower on page, not hero |

## Rejected/unused for visible site
- `assets/hero.webp`, `assets/result-*.webp`: rejected from visible placement because they are 206×206 thumbnails and looked poor enlarged.
- Rio massage images: off-category for the main hair salon visual story and/or watermarked.
- `magic-wix-1.jpg`, `magic-wix-2.jpg`, `magic-wix-7.jpg`: rejected as blank/blurred/abstract or visually weak.
- Map/logo/avatar/product graphics: rejected as non-result or weak marketing assets.
- Duplicate/near-duplicate public social images: not used to avoid visible repetition.
