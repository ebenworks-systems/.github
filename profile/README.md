<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ebenworks-systems/.github/main/profile/assets/banner-dark.png">
  <img alt="Ebenworks. AI for the people the system overlooks. Nine products, one shared platform." src="https://raw.githubusercontent.com/ebenworks-systems/.github/main/profile/assets/banner-light.png" width="100%">
</picture>

Ebenworks is an AI product company building for the people the system overlooks. Its nine products share one engineering layer: sign-in and billing, a model gateway, deployment and monitoring are built once and reused across the products.

[ebenworks.co](https://ebenworks.co) · [Technology](https://ebenworks.co/technology) · [Research](https://ebenworks.co/research) · [Open source](https://ebenworks.co/open-source) · [Security](https://ebenworks.co/security) · [Careers](https://ebenworks.co/careers) · [Contact](https://ebenworks.co/contact)

## Products

| Product | What it does |
|:---|:---|
| <img src="https://raw.githubusercontent.com/ebenworks-systems/.github/main/profile/assets/imali.png" width="28" align="absmiddle" alt="">&nbsp; [Imali AI](https://imali-ai.ebenworks.co/) | A business operating system for African shops and small teams: sales, invoices, stock, staff and books from a WhatsApp chat, with web and Android. |
| <img src="https://raw.githubusercontent.com/ebenworks-systems/.github/main/profile/assets/chingu.png" width="28" align="absmiddle" alt="">&nbsp; [Chingu Care AI](https://chingu-ai.ebenworks.co/) | A Korean voice companion that talks with a senior living alone at one press and tells their family when something changes. The family never sees the words. |
| <img src="https://raw.githubusercontent.com/ebenworks-systems/.github/main/profile/assets/phila.png" width="28" align="absmiddle" alt="">&nbsp; [Phila Health Ecosystem](https://phila-health.ebenworks.co/) | Seven products for practices, clinics, outreach, programmes, districts, hospitals and learning. Offline care records in the shared app. A clinician decides. |
| <img src="https://raw.githubusercontent.com/ebenworks-systems/.github/main/profile/assets/bidwright.png" width="28" align="absmiddle" alt="">&nbsp; [BidWright Tender AI](https://bidwright-ai.ebenworks.co/) | Turns tender documents and company evidence into a requirements report and an editable response, with missing evidence and claims flagged for review before submission. |
| <img src="https://raw.githubusercontent.com/ebenworks-systems/.github/main/profile/assets/statosports.png" width="28" align="absmiddle" alt="">&nbsp; [StatoSports](https://ebenworks.co/products/statosports) | Creates and runs tournaments end to end: groups and knockout brackets, clubs and squads, referee scoring and live standings, with a branded public site for every competition. |
| <img src="https://raw.githubusercontent.com/ebenworks-systems/.github/main/profile/assets/diaspry.png" width="28" align="absmiddle" alt="">&nbsp; [Diaspry Community OS](https://diaspry.ebenworks.co/) | Everything a diaspora association needs to run itself: a branded site, member registry, events, news, a photo archive and committee roles. |
| <img src="https://raw.githubusercontent.com/ebenworks-systems/.github/main/profile/assets/izwi.png" width="28" align="absmiddle" alt="">&nbsp; [Izwi Music OS](https://izwi-os.ebenworks.co/) | The software that runs an independent record label: public site, fan store, catalogue, contracts, royalty splits, payouts and artist logins. |
| <img src="https://raw.githubusercontent.com/ebenworks-systems/.github/main/profile/assets/tzohar.png" width="28" align="absmiddle" alt="">&nbsp; [Tzohar Sites](https://tzohar-sites.ebenworks.co/) | Personal websites for creatives and founders, designed, written, built, launched and maintained, in up to five languages. |
| <img src="https://raw.githubusercontent.com/ebenworks-systems/.github/main/profile/assets/az-dates.png" width="28" align="absmiddle" alt="">&nbsp; [A–Z Dates](https://az.dates.ebenworks.co/) | Twenty-six date ideas per city, one for every letter of the alphabet, with real addresses, maps and insider tips. Free. |

## The shared layer

- **[Njere Engine](https://ebenworks.co/njere)** is our model gateway. Each configuration names a primary provider and its fallbacks; Njere routes the request, moves to the next provider on an outage, a missing model or a rate limit, and checks the structure of every reply before the product receives it.
- **[Ebenworks Accounts](https://accounts.ebenworks.co/)** gives one sign-in for every connected product, with organisations and subscriptions. [Privacy](https://accounts.ebenworks.co/privacy) · [Security](https://accounts.ebenworks.co/security) · [Sub-processors](https://accounts.ebenworks.co/subprocessors)
- **[System status](https://status.ebenworks.co/)** shows whether each product, site and platform service is operating.

## Research

We train computer vision models to segment images from a small set of labelled examples, and release the papers, weights, demos and training code.

- PixCon adds a clean-positive pixel-contrastive branch to a DINOv2-based semi-supervised segmentation pipeline. On Pascal VOC at the 1/8 labelled split it reaches 87.90 mIoU as a three-seed mean. [Paper](https://arxiv.org/abs/2607.03068) · [Code](https://github.com/psychofict/PixCon) · [Project page](https://psychofict.github.io/PixCon/) · [Demo](https://huggingface.co/spaces/psychofict/pixcon-demo)
- CW-BASS v2 measures how reliable a foundation-model teacher's confident pseudo-labels are, then chooses between strict filtering and an adaptive confidence floor. On ADE20K at the 1/8 split the adaptive floor reaches 50.58 mIoU in a single-seed run. [Paper](https://arxiv.org/abs/2608.12773) · [Code](https://github.com/psychofict/CW-BASS-v2) · [Project page](https://psychofict.github.io/CW-BASS-v2/) · [Demo](https://huggingface.co/spaces/hugging-apps/cwbass-v2-segmentation)
- Checkpoints for Pascal VOC, Cityscapes and ADE20K, for both methods, are on [Hugging Face](https://huggingface.co/psychofict).

## Open source

| Project | What it does | |
|:---|:---|:---|
| [hwpkit](https://hwpkit.ebenworks.co/) | Reads, fills, edits and extracts text from Korean HWP and HWPX files in pure Python. MIT, on PyPI. | [Docs](https://hwpkit.ebenworks.co/quickstart/) · [Source](https://github.com/psychofict/hwpkit) |
| [claudehop](https://github.com/psychofict/claudehop) | Moves every terminal to another Claude Code account in one keystroke. One file, no dependencies. MIT, on PyPI. | [Source](https://github.com/psychofict/claudehop) |

## Find us

- Ebenworks: [LinkedIn](https://www.linkedin.com/company/ebenworks) · [Instagram](https://www.instagram.com/ebenworks.co/) · [YouTube](https://www.youtube.com/channel/UChUx7mbGTtumVd1VIaF4i5w) · [Hugging Face](https://huggingface.co/ebenworks) · [Crunchbase](https://www.crunchbase.com/organization/ebenworks) · [Wellfound](https://wellfound.com/company/ebenworks)
- Imali AI: [Instagram](https://www.instagram.com/imali.africa/) · [Threads](https://www.threads.com/@imali.africa) · [X](https://x.com/imaliafrica)
- Chingu Care AI: [Instagram](https://www.instagram.com/chingucare.ai/) · [Threads](https://www.threads.com/@chingucare.ai)
- Phila Health Ecosystem: [Instagram](https://www.instagram.com/phila.healthcare/) · [Threads](https://www.threads.com/@phila.healthcare) · [YouTube](https://www.youtube.com/@phila.health)
- BidWright Tender AI: [Instagram](https://www.instagram.com/bidwright.app/) · [Threads](https://www.threads.com/@bidwright.app)
- StatoSports: [Instagram](https://www.instagram.com/statosports/) · [Threads](https://www.threads.com/@statosports)
- Diaspry Community OS: [Instagram](https://www.instagram.com/diaspry.community/) · [Threads](https://www.threads.com/@diaspry.community)
- Izwi Music OS: [Instagram](https://www.instagram.com/izwi.music/)

Write to [contact@ebenworks.co](mailto:contact@ebenworks.co), or start a brief at [ebenworks.co/start](https://ebenworks.co/start).
