# Neon Scrap website

Public landing page, support and privacy policy for the iPhone/iPad game.

Published by GitHub Pages from the root of `main`: https://truizlop.github.io/neon-scrap-site/

This repository contains only public website content and selected marketing assets. The game source lives in a separate private repository. No dependencies or build step are required.

To preview locally with the production project path, serve the parent directory and make a `neon-scrap-site` symlink to this directory, or use a static server with that base path.

## Visual direction

The landing page pairs the shipping brush wordmark and a native duel with a short introduction to same-device play. A second native garage capture supports the controls and vehicle explanation. The final section separates the free content from the optional Season 1 purchase. The owner rejected the oversized cover illustration, detached vehicle lineup and overly sparse copy; keep useful text alongside relevant images.

Gameplay and garage images are actual native app captures staged for marketing, not images generated for this website. Screenshots keep their full native proportions. Layout concepts are design references only and must not replace the original screenshots. WebP assets are self-hosted; there are no third-party scripts, fonts, trackers or build dependencies.

Keep copy specific: explain the two controls, shared launch, pickups, wrapped edges and free/paid contents in short passages. Avoid slogan triplets, generic feature cards, fabricated testimonials and decorative calls to action. The App Store message remains coming-soon text until the app is released. Support and privacy keep their detailed information on their own pages.

The September 23 revision uses cream, ink, coral and mint with condensed display headings, simple rules and an annotated game screenshot. It was checked in the Codex browser on desktop, tablet and narrow phones, including image proportions, overflow, section links, support/privacy navigation and keyboard access.

## Season 1 catalog

The expanded purchase section names all eight paid rides, their starting weapons and all four paid arenas. Vehicle/weapon pairings and arena names match the shipping game data. Keep the distinction explicit: Season 1 adds vehicle choices and arenas; all weapon pickups remain available in the free game. The purchase is permanent for both local players on the same device, with no subscription.

Vehicle portraits use measured SVG view boxes into the existing `roster.webp` artwork. Keep their intrinsic aspect ratios so adjacent vehicles cannot enter the viewport. Arena previews use four 600×900 native SceneKit renders, exported from the corrected purchase-panel preview in `SeasonStoreTests.testArenaCatalogPreservesCoverLayoutAndCompleteOverheadFraming`. Their canonical 18×27 arena bounds preserve cover positions, dimensions and rotations, with a strict overhead orthographic camera. Keep the full 2:3 image proportions. Never compress the simulation bounds to fit a landscape thumbnail: that moves full-size cover into overlapping clusters. Names and descriptions remain selectable HTML text. These are staged arena previews, not human match captures.
