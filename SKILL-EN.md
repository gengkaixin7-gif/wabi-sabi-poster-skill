---
name: bilingual-product-posters
description: Create bilingual Chinese and English ecommerce posters from product images, brand materials, and verified specifications using a quiet, minimal, vintage wabi-sabi aesthetic with natural materials and traces of time. Use for wabi-sabi, natural, tactile, restrained, retro-minimal, still-life, or bilingual product-poster requests, especially when reducing glossy tech or aggressive promotional styling. Do not use for simple text replacement, white-background product listings, neon tech visuals, or direct imitation of a reference brand layout.
---

# Bilingual Wabi-Sabi Product Posters

## Purpose and boundaries

Place a real product in a quiet, breathable natural setting. Use imperfect materials, softly aged colors, and restrained typography to express time, tactility, and everyday use. Wabi-sabi is a system of visual choices, not permission to add arbitrary damage, dirt, or Japanese cultural symbols.

- Chinese: default to a people-free product still life built around the product, materiality, and complete Chinese information.
- English: retain a restrained interaction between a person and the product. The gesture should feel quiet, credible, and undramatic. Choose either a minimal headline layout or a detailed information layout.
- Compose the Chinese and English posters independently; do not merely replace the text on one shared image. They should share product facts, brand constraints, a color family, and a consistent material mood.
- Preserve the product's real shape, color, construction, logo, and function. Age and imperfection may affect the environment, paper, props, or lighting, but must not make a new product appear damaged or secondhand unless the user explicitly requests it.
- Generate images only when the user asks for posters. Installing, editing, or discussing this skill does not trigger image generation.

## Inputs and defaults

Read the product images, logo, brand guidelines, product name, headline, benefits, specifications, price, currency, dates, offer conditions, and placement context. Samples and references demonstrate methods only; never treat them as facts about the current product.

| Option | Available values | Default |
| --- | --- | --- |
| Output language | Chinese and English / Chinese only / English only | Chinese and English |
| English version | Minimal headline / Detailed information / Both | Detailed information |
| English interaction | Real use / Quiet companionship / Symbolic scale | Choose the most credible option for the product |
| Wabi-sabi direction | Warm natural / Cool limewash / Dark handcrafted | Warm natural |
| Ratio and size | User-specified | Portrait 4:5, 1600 x 2000 PNG |

The default delivery is one Chinese poster and one detailed English poster. Follow the user's request when they ask for one language or multiple English versions. Preferences never override factual accuracy. If a required quantity or field is contradictory and cannot be inferred, ask only about that conflict while continuing any independent preparation.

## Required reading and branch routing

Before producing any poster, read in this order:

1. [Wabi-Sabi Art Direction](references/wabi-sabi-art-direction.md) for the shared aesthetic, materials, palette, lighting, composition, typography, and exclusions.
2. [Product Extraction and Scene Compositing](references/production-compositing.md) for the quality threshold for placing a real product into a scene.
3. The reference for the current output branch:

| Output branch | Required file | Content boundary |
| --- | --- | --- |
| Complete Chinese product poster | [Chinese Product Style](references/chinese-product.md) | People-free still life; product name, theme, benefits, and any supplied transaction details |
| Minimal English headline poster | [English Minimal Style](references/english-minimal.md) | Person and product, one editorial headline, and one compact identity group |
| Detailed English information poster | [English Detailed Style](references/english-detailed.md) | Human interaction, full product name, core benefits, and supplied transaction details |

Read only the branch references needed for the actual output. When producing both English versions, plan their information spaces separately; do not create the minimal version by simply deleting text from the detailed version.

## Wabi-sabi decision order

Make decisions in this order: product fidelity -> factual accuracy and legibility -> composition and negative space -> materials and light -> decoration.

- Give each poster one visual focal point and one primary typographic focal point. Emphasize no more than three secondary information items.
- Use tactile materials such as limewash, unglazed ceramic, aged wood, linen, fibrous paper, unpolished stone, or oxidized metal, but choose only two or three per poster to avoid a collage of natural materials.
- Slightly irregular edges, subtle print misregistration, paper fibers, fine grain, and asymmetrical balance are acceptable. Keep them understated so the result never feels dirty, broken, cheap, or unclear.
- Light should resemble window light or soft overcast light: a clear direction, gentle contrast, and visible shadows. Avoid neon, cyberpunk light trails, directionless glow, and stacks of mirror-like highlights.
- Build the palette from muted earth tones, bone white, smoky gray, charcoal, moss green, clay red, and the product's real color. Use at most one accent color, sampled from the brand or product.
- Negative space is active, not empty. Use wall texture, patches of light, shadows, and object spacing to establish rhythm. Do not fill the image with frosted cards, pill labels, specification tables, or promotional stickers.
- Do not equate wabi-sabi with Zen, generic Japanese styling, rock gardens, brush calligraphy, or Japanese text. Do not add bamboo, cherry blossoms, shoji screens, or tea-ceremony objects unless the product and supplied materials genuinely call for them.

## Facts, translation, and typography

- The full product name must appear independently and legibly on every final poster. A brand, model number, or slogan does not replace it.
- Use only supported benefits, prices, currencies, dates, certifications, and performance claims. Never invent information to complete the design.
- When source copy exists in both languages, use each source version. When only one language exists, translate faithfully and preserve brand names, model numbers, numerals, units, qualifiers, and price conditions.
- English does not imply a U.S.-dollar market; never convert currency without instruction. Clarify ambiguous numeric dates with month names without changing the date range.
- Use the generative model only for text-free backgrounds and required visual material. Add final text, numerals, logos, and functional icons through editable, deterministic layout.
- Chinese and English may share a typographic mood without using the same typeface. Prefer warm serif or Song-style type paired with a restrained sans serif, and use no more than two type families. Do not use calligraphy as superficial “Eastern” decoration.

## Workflow

1. Build a fact table with each item's source, language, display requirement, and immutable wording.
2. Confirm language, English version, wabi-sabi direction, and deliverable count. Write one design concept sentence for each poster.
3. Read the shared and branch references, then prepare a five-part photographic plan covering materials, palette, lighting, composition, and information. Explain why these choices suit the product.
4. Extract the real product precisely, reserve safe areas for the headline, full product name, and required details, then generate a text-free scene.
5. Composite the product and rebuild contact shadows, environmental reflections, and shared color temperature. Verify that it occupies the scene rather than appearing pasted on top.
6. Add text, logo, and any required icons in an editable form. Establish hierarchy primarily through size, weight, spacing, and alignment; use containers sparingly.
7. Review at full size and phone-thumbnail size for product fidelity, naming, text, edges, negative space, materials, lighting, and wabi-sabi consistency. Correct the relevant layer instead of explaining a defect in prose.
8. Export PNG files and preserve the transparent product cutout, text-free background, editable typography or composition script, font notes, and final prompt. Use `product_zh`, `product_en_minimal`, and `product_en_detailed` filenames without overwriting earlier versions.

## Final acceptance criteria

- The product, full product name, and primary theme are visible within three seconds and remain legible at phone size.
- Product structure, color, logo, and details match the references, with no invented ports, accessories, wear, or materials.
- The scene provides credible support, a coherent light source, contact shadows, and environmental reflections. Product edges have no white fringe or original-image rectangle.
- Natural materials and traces of time are present while the image remains clean, premium, and quiet rather than dirty, distressed, or filter-heavy.
- The asymmetrical composition remains balanced, negative space is generous, and cards, badges, icons, and decorations are restrained.
- Chinese output contains no person; English output includes a credible, restrained interaction between a person and the product. Each image stands alone while belonging to one series.
- All prices, dates, units, and qualifiers match the source. No sample or reference-poster content has been carried into the current product.

## Invocation examples

- “Use these product photos to make a bilingual wabi-sabi poster set.” -> one complete Chinese still-life poster and one detailed English human-interaction poster.
- “English only, minimal and vintage, with someone using the product gently and no promotional feel.” -> minimal English headline poster.
- “The Chinese poster needs a price and three specifications, but it should not look like a conventional ecommerce specification table.” -> complete Chinese information organized through space, type scale, and natural grouping.
- “No Japanese motifs; use only natural materials, aged paper, and quiet light.” -> retain the wabi-sabi method while explicitly excluding cultural symbols.
