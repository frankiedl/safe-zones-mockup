# Safe zone values: sources and confidence

Reviewed October 2026. Values are in pixels on a 1080×1920 canvas, written as **top / bottom / left / right**.

## Ads (official guidelines or official templates)

| Platform | Values | Source | Confidence |
|---|---|---|---|
| Instagram Reels | 270 / 672 / 65 / 65 (14 % / 35 % / 6 %) | Meta's guidance for Reels ads, cited consistently by [adnova.ai](https://adnova.ai/blogs/meta-ad-safe-zones-guide), [AdNabu](https://blog.adnabu.com/meta-ads/meta-safe-zones/) and [Billo](https://billo.app/blog/meta-ads-safe-zones). Meta's help page ([facebook.com/business/help/980593475366490](https://www.facebook.com/business/help/980593475366490)) blocks automated reading, so it could not be quoted directly. | Medium |
| Instagram Stories | 270 / 384 / 65 / 65 (14 % / 20 % / 6 %) | Same Meta guidance. Billo and AdNabu claim that in March 2026 Meta unified the Stories and Reels safe zones (35 % bottom), but neither cites a Meta announcement, and AdNabu's own cheat sheet still lists 20 %. Not applied by default. | Medium |
| Facebook Reels | 270 / 672 / 65 / 65 | Meta applies the same guidance to Facebook and Instagram Reels. | Medium |
| Instagram / Facebook Feed 4:5 | 0 / 0 / 34 / 34 inside the 1080×1350 post | The interface does not cover a feed post. Side margins show the 3:4 profile grid crop (1012×1350), calculated geometrically. | High |
| TikTok In-Feed | 240 / 660 / 120 / 120, plus the action column x 780–1080 from y 840 | TikTok Ads In-Feed template (annotated at 720×1280 as 160 / 440 / 80 / 80 with a 120 px action column, scaled ×1.5), reported by [adchecklab.com](https://adchecklab.com/articles/tiktok-safe-zone-dimensions-2026), which cites [TikTok Ads Help: In-Feed Ads](https://ads.tiktok.com/help/article/tiktok-auction-in-feed-ads?lang=en). The template file itself could not be opened for verification. Older values circulating online (150 / 440 / 60 and 220 / 480 / 250 right) appear to be outdated. | Medium |
| YouTube Shorts | 288 / 672 / 48 / 192 | Google Ads Help, "Universal safe zones for video ads on YouTube" ([support.google.com/google-ads/answer/13547298](https://support.google.com/google-ads/answer/13547298)). Google gives the values only inside its diagram and PNG template. [adchecklab.com](https://adchecklab.com/articles/youtube-shorts-safe-area-dimensions) and [recruitmentads.com](https://recruitmentads.com/free-tools/ad-mockup/youtube) measured the template independently and agree on these numbers. | Medium-high |

## Organic (no official values exist)

| Platform | Values | Source | Confidence |
|---|---|---|---|
| Instagram Reels | 280 / 440 / 60 / 170 | Estimate measured on the interface | Low |
| Instagram Stories | 270 / 384 / 65 / 65 | Same as ads | Medium |
| Facebook Reels | 280 / 500 / 60 / 170 | Estimate measured on the interface | Low |
| TikTok | 200 / 334 / 86 / 140 | In-app measurement published by [adchecklab.com](https://adchecklab.com/articles/tiktok-safe-zone-dimensions-2026) | Low |
| YouTube Shorts | 380 / 390 / 60 / 201 | In-app measurement published by [adchecklab.com](https://adchecklab.com/articles/youtube-shorts-safe-area-dimensions) | Low |

## Confidence levels

- **High**: derived from geometry or from a source that could be read and verified directly.
- **Medium-high**: an official source whose exact numbers were confirmed by two independent measurements.
- **Medium**: an official guideline reported consistently by several secondary sources, where the primary source could not be read directly.
- **Low**: a measurement of the app interface, by a third party or by the author. These change with app versions.

If you can verify any of these against the primary source, please open an issue or a pull request with the link.
