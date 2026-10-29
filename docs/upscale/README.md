# BlueChip — 8K wallpaper edition

Eleven quality-95 WebP wallpapers: ten theme designs at 8192 × 5120 (16:10), plus Stars and Stripes Flight at 8192 × 4608 (16:9) in optional/. No composition was cropped to change its aspect ratio.

## Eagle entrance

The five-second preview shows one curved, layered eagle swoop, settling completely by 2.8 seconds. The intro video lasts approximately three seconds at 1920 × 1200, 30 fps. The endpoint is the resized PNG master used to encode the 8K WebP still. This is a 2D glide with painted smoke artwork, not articulated wing animation or a smoke simulation. Nothing loops after the entrance.

For an Omarchy version supporting background intros, place backgrounds/04-maximum-freedom.webp and backgrounds/intros/04-maximum-freedom.mp4 inside the BlueChip theme. Matching stems are required. The current upstream intro resolver supports this pairing and respects animation settings. Actual desktop playback has not been tested on your machine. The WebP works independently as a static wallpaper.

## Collaboration shortlist

Recommended default: 00-pressed-metal-monochrome. Recommended alternate: 02-collaboration-laser-etched. The coloured 01-collaboration-pressed-metal remains available; it is the least distinct of the three. All are included for comparison.

## Enhancement details

00–03 were rendered directly from the supplied SVG artwork at the export size, preserving logo geometry. 04–10 received two contextual image-edit passes: nine overlapping first-pass crops and four focused second-pass regions each. Every edit used the complete supplied source as context. Native generated crops are smaller than 8K; these are assembled 8K exports with AI-reconstructed detail and resampled fallback areas.

Registration was bounded to 2% scale and 0.4° rotation, followed by local confidence masks, restrained colour correction and feathering. Unreliable regions retained earlier pixels. The quiet eagle background, a foundry foreground edge, a blueprint stamp and the aircraft sky received conservative fallbacks. Source-limited regions remain softer at 100% magnification. The final refinement strength for 06–10 was reduced to 45% to make detail transitions less abrupt. Exact counts, native dimensions and hashes appear in ../wallpaper-manifest.json; processing-settings-and-prompts.json contains the edit prompts and registration decisions. Detailed prompts, original sources, intermediate masters, masks, native attempts and review images are retained separately in the saved processing archives.

The optional aircraft image retains its supplied framing and photographic treatment. Its sky is preserved from the supplied photograph. The added microdetail is interpretive; it is not evidence of actual aircraft construction.

## Use

Back up any existing wallpapers before replacing files. Copy selected WebP files into the installed theme's backgrounds directory. Copy the intros directory alongside them for the eagle entrance. Copy the optional aircraft WebP into backgrounds only if you want it in the wallpaper rotation. This pack contains wallpaper assets, not a replacement theme configuration.

This update includes the wallpaper assets and preview in the repository. Live desktop acceptance remains pending.

## WebP delivery

All eleven wallpapers use quality-95 WebP (method 6), preserving their 8K dimensions. Combined wallpaper size falls from 272.5 MB to 47.1 MB (82.7% smaller). This is lossy delivery compression; lossless PNG masters remain in the previously saved wallpaper pack. Decoded dimensions and hashes are recorded in the manifest. Full-size comparison crops were inspected for the logo, eagle and aircraft.
