# Research folder: "Is HomeView the next Apple Watch?"

Everything referenced while building [HomeView attached bets.html](../HomeView%20attached%20bets.html) and the LinkedIn post.

## Folder map

| Folder | Contents |
| --- | --- |
| [source-files/](./source-files) | The two case-study documents that all facts, figures and feature timelines come from |
| [images/](./images) | Local copies of the product images used on the page (web-sized, up to 960 px wide) |
| [webpages/](./webpages) | Saved Wikimedia Commons description pages for each image (HTML, as fetched on 10 Nov 2026) |
| [licence-metadata/](./licence-metadata) | Commons API output per image: author, licence, original file URL and size |
| [cited-sources/](./cited-sources) | PDF and HTML copies of the sources the case study cites, with a verification table |

## 1. Source documents

| File | Used for |
| --- | --- |
| [Attached Bets with meta_Apple Watch, AirPods, Tesla Powerwall.md](./source-files/Attached%20Bets%20with%20meta_Apple%20Watch%2C%20AirPods%2C%20Tesla%20Powerwall.md) | Final source. Positioning arcs, version-by-version feature tables, install milestones, Meta glasses and VR/AR story, anchor and dependency analysis |
| [Attached Bets Apple Watch, AirPods, Tesla Powerwall.md](./source-files/Attached%20Bets%20Apple%20Watch%2C%20AirPods%2C%20Tesla%20Powerwall.md) | Earlier version without the Meta case. The first fact-check of the draft post and the first HTML build used it |

The same case study also exists as a PDF in the parent folder (`Attached Bets Apple Watch, AirPods, Tesla Powerwall.pdf`). It was not read for this work.

### Sources cited inside the case study

Archived copies, a line-by-line verification of the headline figures and the list of sources that could not be obtained are in [cited-sources/README.md](./cited-sources/README.md). Summary: Apple and Tesla filings, Energy-Storage.News, Electrek, IDC, UploadVR, Six Colors, Meta's help center and launch coverage are saved as PDFs; Tesla's Q3 deck, Apple's own announcement, TechRepublic, TechSpot, "AI Wiki" and the Meta unit-count aggregator were not obtained.

## 2. Images used on the page

Fetched from Wikimedia Commons on 10 Nov 2026. Each row links to the saved page and its licence data.

| Local file | What it shows | Author | Licence | Used in | Saved page | Metadata |
| --- | --- | --- | --- | --- | --- | --- |
| [watch-2015.jpg](./images/watch-2015.jpg) | Original Apple Watch Sport on display (2015) | thomersch | CC BY 4.0 | Positioning, feature growth, spectrum, summary | [html](./webpages/watch-2015.html) | [json](./licence-metadata/watch-2015.json) |
| [watch-ultra3.jpg](./images/watch-ultra3.jpg) | Apple Watch Ultra (Commons file title says Ultra 3, 2026) | Gpkp | CC BY-SA 4.0 | Feature growth | [html](./webpages/watch-ultra3.html) | [json](./licence-metadata/watch-ultra3.json) |
| [airpods-pro-1.jpg](./images/airpods-pro-1.jpg) | AirPods Pro | aconcagua | CC BY-SA 4.0 | Positioning, feature growth, spectrum, summary | [html](./webpages/airpods-pro-1.html) | [json](./licence-metadata/airpods-pro-1.json) |
| [airpods-pro-case.jpg](./images/airpods-pro-case.jpg) | AirPods Pro charging case | aconcagua | CC BY-SA 4.0 | Feature growth | [html](./webpages/airpods-pro-case.html) | [json](./licence-metadata/airpods-pro-case.json) |
| [powerwall-2.jpg](./images/powerwall-2.jpg) | Tesla Powerwall 2 on display | Raysonho | CC0 | Positioning, feature growth, spectrum, summary | [html](./webpages/powerwall-2.html) | [json](./licence-metadata/powerwall-2.json) |
| [megapack.webp](./images/megapack.webp) | Concept rendering of a Megapack site with solar canopies (a rendering, not a photo) | Wikideas1 | CC0 | Feature growth | [html](./webpages/megapack.html) | [json](./licence-metadata/megapack.json) |
| [quest-2.jpg](./images/quest-2.jpg) | Oculus Quest 2 on a store display, branded "Oculus from Facebook" | KKPCW | CC BY-SA 4.0 | Positioning, feature growth (Meta anchor) | [html](./webpages/quest-2.html) | [json](./licence-metadata/quest-2.json) |

CC BY-SA images (Ultra, both AirPods, Quest 2) must keep the same licence and attribution if the page is reused. The page shows credits under each image and in the footer.

### Considered but not used

| Candidate | Licence | Why not used | Saved page |
| --- | --- | --- | --- |
| AppleWatchAppleStore.jpg (Raysonho) | CC0 | The Watch Sport photo was chosen for the 2015 original | [html](./webpages/considered-watch-applestore.html) |
| Tesla Powerwall Render.svg (Jzh2074) | CC BY-SA 4.0 | The Powerwall 2 photo was chosen | [html](./webpages/considered-powerwall-render.html) |

### Still to supply

- `images/meta-glasses.jpg`: Meta glasses. Commons searches returned only photos taken with the glasses, not photos of them.
- `images/homeview.jpg`: HomeView, which is not covered by any source here.

Both go in the parent [images/](../images) folder, which the HTML reads.

## 3. How the Commons candidates were found

Searches on the Wikimedia Commons API (`action=query`, file namespace), run 9 Nov 2026:

- `Apple Watch Series`, `Apple Watch Ultra OR "Apple Watch Series 4" OR "AirPods Max" OR "AirPods 4"`
- `AirPods Pro`
- `Tesla Powerwall`, `Tesla Megapack`
- `Ray-Ban Meta smart glasses` and a title search for Ray-Ban Stories, Ray-Ban Meta, Meta Ray-Ban Display, Oakley Meta (no usable product photos)
- `Oculus Quest OR "Meta Quest" headset`

## 4. Not in this folder

- No HomeView sources exist. Its position in the anchoring spectrum and the "repeat" conclusion rest only on the premise in the post: a household product whose personalised experience depends on paired Apple devices.
- Feature-area tagging, radar scores and spectrum positions are analyst judgment built on the source documents.
