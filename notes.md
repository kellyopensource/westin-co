## 13 Jul 2026

***What I did:*** 
W & Co's business is more custom than the initial database plan. She may purchase 10 of item A and 20 of item B. Then sell half and not reorder due to minimums or new product replacements. Developing custom products includes a constantly varying inventory in small lots. For sized items, there may be some items in some colors, without a backup. I decided to stop working on the architecture noted and first explore new AI within the Shopify stack to get W & Co some relief on daily operations. 

***What's next:***
# Shopify Features for Westin & Co: A Developer-Mode Priority List


The list below is ordered by expected impact for this specific business — not by feature popularity — starting with the change that removes the most customer friction per hour of setup time.

## Ranked Feature & App List

| # | Feature / App | Free (native) or Paid (3rd-party) | Cost | Why it matters here |
|----|----|----|----|----|
| 1 | **Continue selling when out of stock** + custom "ships when restocked" messaging | Free — native Shopify setting | $0 | This is the single setting that stops a sold-out size from silently blocking a sale. Applied per-variant, it lets a customer order a size that's temporarily at zero while Claudia is between batches, rather than seeing a dead "Sold Out" button ([Shopify Community](https://community.shopify.com/t/pre-order-for-out-of-stock-product-variants/408435), [PreProduct](https://preproduct.io/out-of-stock-on-shopify-what-to-do-and-how-to-keep-selling/)). |
| 2 | **Pre-order / back-in-stock waitlist app** (e.g., STOQ, Amp: Back in Stock & PreOrder+) | Paid | Free tier available; paid tiers ~$10-$69/mo (STOQ: $10/$29/$69) | Converts "sold out" into either a captured pre-order or a waitlist signup at the variant level, so Claudia knows exactly which size/color combo has real demand before she places her next 10-12-unit order — turning guesswork into a demand list ([STOQ pricing](https://www.stoqapp.com/pricing), [apps.shopify.com/back-in-stock](https://apps.shopify.com/back-in-stock)). |
| 3 | **Locked-position product personalizer** for embroidery text/thread color with live preview (e.g., Easify Product Options, Zepto Product Personalizer, Bespo) | Paid (all have usable free or near-free tiers) | Easify: free forever plan, Pro $9.99/mo; Zepto: from $9.99/mo; Bespo: embroidery-specific, no-code | This is the direct replacement for the 2-10 text exchanges per order. The customer picks thread color, types their text, and sees a live preview on the product image before adding to cart — Claudia reviews the order instead of negotiating it by text ([Shopify Community example](https://community.shopify.com/t/looking-for-a-product-personalization-app-for-embroidery-with-fixed-text-position-and-character-based-pricing/631600), [Easify pricing](https://easifyapps.com/docs/pricing-plans/), [Bespo](https://apps.shopify.com/bespo)). |
| 4 | **Low-stock alert + reorder-point forecasting app** (e.g., Stockie) | Paid | Free plan (250 variants, 1 alert); paid $4.99-$59.99/mo scales to forecasting + auto purchase orders | Directly targets the "no solid inventory number" problem — it uses actual sales velocity to suggest when and how much to reorder, which is the missing piece before any smarter automation can work reliably ([Stockie pricing](https://apps.shopify.com/stockie)). |
| 5 | **Native color/image swatches via category metafields** | Free — native Shopify (no app needed on current themes) | $0 | Lets shoppers see at a glance which colorways actually exist for a product without opening every variant — reduces "does she have it in pink" questions before they're even asked ([Shopify Help Center](https://help.shopify.com/en/manual/custom-data/metafields/category-metafields/using-category-metafields), [Reddit merchant thread](https://www.reddit.com/r/shopify/comments/1pzodjw/image_swatches_for_variant_selection/)). |
| 6 | **Guided product-finder quiz** (e.g., QuizCraft, Quiz Kit, RevenueHunt) | Paid, but strong free tiers | QuizCraft: free (1 quiz/50 completions), $9.99-$49.99/mo beyond that; Quiz Kit: $59+/mo | Puts the customer in "pick a few answers" mode (style, size range, occasion, color) and routes them to matching in-stock products — this is the self-service layer that turns Claudia into a reviewer of finished picks rather than a live product-matching service ([QuizCraft pricing](https://apps.shopify.com/quizcraft-smart-product-finder), [Quiz Kit pricing](https://apps.shopify.com/quiz-kit)). |
| 7 | **Shopify Magic — AI image editing (background removal/cleanup)** | Free — native, included on every plan | $0 | Any usable raw photo (including phone shots or pulled Instagram images) can get a quick background clean-up directly in the product editor without a separate tool, which matters given how many products currently have no product-ready photo at all ([Clyro guide](https://www.clyro.com/blog/shopify-magic-ai-guide), [PageFly](https://pagefly.io/blogs/shopify/shopify-magic)). |
| 8 | **Instagram-to-Shopify photo/UGC import app** (e.g., SocialFlux, Instafeed, Foursixty) | Paid (free tiers exist on most) | Typically free-$20/mo entry tier; scales with volume | Solves the missing-photo problem at the source — these apps sync your existing Instagram content into the Shopify admin so images can be reused instead of restaged, and can tag products directly on the imported media ([SocialFlux](https://apps.shopify.com/socialflux), [Foursixty guide](https://foursixty.com/blog/add-instagram-photos-to-shopify-product-pages/)). |
| 9 | **Shopify Sidekick (AI store assistant)** | Free — native, included on every plan | $0 | A conversational assistant inside the admin that Claudia (or you) can ask things like "what sold out this week" or "draft a restock list," and that can execute multi-step admin tasks in the background — useful given her limited available time ([Shopify Help Center](https://help.shopify.com/en/manual/shopify-admin/productivity-tools/sidekick), [Ringly.io](https://www.ringly.io/blog/ai-sidekick-shopify)). |
| 10 | **Facebook & Instagram sales channel (official Meta app)** | Free — native Shopify sales channel | $0 | Automatically syncs the Shopify product catalog to Instagram/Facebook Shop, keeping product availability consistent across the platform where she already posts most of her photos, without duplicate manual entry ([Shopify Help Center](https://help.shopify.com/en/manual/online-sales-channels/social-commerce/facebook-instagram-by-meta/publishing-products), [Shopify blog](https://www.shopify.com/blog/how-to-sell-on-instagram)). |
| 11 | **Shopify Flow (automation builder)** | Free on Basic plan and above | $0 (included) | Can automate repetitive rules once inventory data is cleaner — e.g., auto-tag a product "low-stock" or move it to the bottom of a collection when a threshold is hit, without custom code ([Mastroke overview](https://blog.mastroke.com/shopify-ai/shopify-ai-toolkit-explained-how-smart-merchants-use-ai-agents-to-grow-faster-in-2026/)). |
| 12 | **Bulk AI background remover / PNG converter** (e.g., Photoroom, Pixelcut, or the in-admin [Cutout.Pro](http://Cutout.Pro) Shopify app) | Paid (light usage often free) | Free tiers common; [Cutout.Pro](http://Cutout.Pro) Shopify app processes batches directly in admin | This is the actual mechanism for turning raw Instagram JPGs into clean, consistent transparent-background PNG product images at volume, rather than one photo at a time through Shopify Magic ([Cutout.Pro Shopify app](https://www.cutout.pro/remove-background/bulk-background-remover), [Pixelcut bulk tool](https://www.pixelcut.ai/bulk/background-remover), [Photoroom batch tool](https://www.photoroom.com/batch/background-remover)). |

## Reading the Order

Items 1-4 target the inventory-mismatch problem directly (sold-out variants, demand capture, personalization instead of texting, and reorder timing). Items 5-8 target the "customer can't self-serve because there's no photo or clear way to compare options" problem. Items 9-12 are free or low-cost accelerants that make the first two groups faster to run day-to-day. Setting up items 1, 2, and 3 in week one would resolve the most customer-facing friction fastest; item 4 (inventory forecasting) is what eventually makes the whole system self-sustaining once there's real sales-velocity data behind it.

## Photo Pipeline To-Do List (Instagram → Clean PNG → Shopify)

Given that a large share of usable product photography already exists on Instagram but not in a catalog-ready format, this is the specific sequence to close that gap:

1.  **Confirm Instagram is a Business or Creator account** linked to a Facebook Page — this is a hard prerequisite for any import tool or the native Shop channel sync ([Shopify Help Center](https://help.shopify.com/en/manual/online-sales-channels/shop/marketing/posts), [Juicer guide](https://www.juicer.io/blog/how-to-connect-instagram-to-shopify)).

2.  **Audit existing products** and flag which ones have zero usable photos versus which just need a background cleanup — a simple tag like `no-photo` in Shopify admin makes this visible at a glance.

3.  **Connect Instagram to the Shop channel** (native, free) to auto-pull the last 90 days of Reels, image posts, and carousels into Shopify as a starting media pool, or install a dedicated import/UGC app (SocialFlux, Instafeed, Foursixty) if product-level tagging on the imported photos is needed ([Shopify Help Center](https://help.shopify.com/en/manual/online-sales-channels/shop/marketing/posts)).

4.  **Batch-process the pulled images** through a bulk AI background remover ([Cutout.Pro](http://Cutout.Pro)'s Shopify app for in-admin batches of 10, or Photoroom/Pixelcut for larger external batches) to generate consistent transparent or white-background PNGs ([Cutout.Pro](https://www.cutout.pro/remove-background/bulk-background-remover), [Pixelcut](https://www.pixelcut.ai/bulk/background-remover)).

5.  **Assign the cleaned PNGs** to the correct product and variant in Shopify admin — note that Shopify allows only one image per variant natively, so plan the primary image per variant deliberately ([Meta Business Help Center](https://www.facebook.com/business/help/1638980739993011)).

6.  **Run remaining rough photos** (phone shots, low light, busy backgrounds) through Shopify Magic's built-in image editor one at a time for quick touch-ups when a bulk tool isn't warranted ([Clyro guide](https://www.clyro.com/blog/shopify-magic-ai-guide)).

7.  **Set a lightweight forward-going habit**: whenever Claudia posts a new product to Instagram, that same photo gets pulled into the pipeline within the week rather than letting the photo backlog regrow — this can be as simple as a recurring reminder rather than new tooling.

8.  **Use Shopify Magic to auto-generate alt text and short descriptions** for each newly added image/product so SEO and accessibility aren't an afterthought ([Xpertshire guide](https://xpertshire.com/blog/shopify-magic-product-descriptions/)).

## Second-Tier Action Items (Bigger Structural Impact, Once Time Allows)

These require more setup time but address the underlying data gap rather than just the symptoms:

- **Physical inventory count + reconciliation pass.** A one-time stocktake (using a barcode-scanning app like BR Stock Take, or Stocky if she ever moves to Shopify POS) to establish a real starting inventory number is the prerequisite for every forecasting feature above actually being accurate rather than guessed ([Shopify inventory reconciliation guide](https://www.shopify.com/blog/inventory-reconciliation), [BR Stock Take](https://apps.shopify.com/stock-take)).

- **Raw-material inventory tracking** (e.g., Materials Inventory app) for blanks/thread stock specifically, since her constraint is really "minimum order to reorder blanks," not just finished SKUs — tracking raw material levels would let a reorder-point app calculate real lead time automatically ([Materials Inventory app](https://apps.shopify.com/materials-inventory)).

- **Automated purchase-order drafting** (Stockie's Pro Plus tier, or a dedicated tool like [Genie.io](http://Genie.io)) once sales velocity data is clean enough — Claudia would approve a drafted reorder quantity instead of calculating minimums manually.

- **Sidekick Pulse proactive monitoring** — once store data is clean, this Shopify-native layer surfaces "you should look at this" alerts (trending product, declining segment) without anyone asking, reducing the need to manually check dashboards ([FirstPier](https://www.firstpier.com/glossary/shopify-magic)).

- **Extend the same guided-quiz + personalizer pattern to caps** once t-shirt and sweatshirt flows are proven, since caps were already flagged as the broadest inventory category and would benefit most from demand-capture (pre-order/waitlist) before launch.

- **Cross-post the cleaned photo pipeline to TikTok Shop**, which now supports syncing Instagram carousels directly into shoppable posts — since the photo pipeline above already produces clean, product-tagged images, this is a low-additional-effort second sales channel ([LinkedIn post on TikTok/Instagram sync](https://www.linkedin.com/posts/tiktok-shop-expert-rehman_tiktokshop-shopify-ecommerce-activity-7421273284052180992-54r4)).

***What was confusing or needs research:***
She doesn't have a formal inventory system. However, a formal inventory system is not her priority. Meeting demand is key and her pain point is the numerous touchpoints per customer due to customization. Also, she is now invited to larger events where the PoS needs to be faster. We are adjusting to immediate relief and will then continue back to establishing inventory tracking.

***Files I changed:***
None for this tracking note.



## [DATE]

***What I did:***
-

***What's next:***
-

***What was confusing or needs research:***
-

***Files I changed:***
-

---
