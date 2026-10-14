# Business website

A small-business website with service cards, sample pricing, testimonials and a sample contact form.

Adapted from [StartBootstrap/startbootstrap-business-frontpage](https://github.com/StartBootstrap/startbootstrap-business-frontpage/tree/b330ff68d31fca0950dcce5687796d71432fbd5f). Template code is MIT; original copyright and license are retained in [LICENSE](LICENSE). Lyre's server, sample artwork and adaptations are MIT too.

## Run locally

Install Node 22 or newer, then run `npm start` and open http://127.0.0.1:4173. There are no npm dependencies to install and no account, database or API key is needed. To change the port, set `PORT` before starting. Stop with Ctrl+C.

In Lyre on your computer, use Marketplace → this template → **Choose folder & install** on a version containing this reviewed recipe. Lyre prepares its own Node runtime and opens the project. You can also use Add project → Clone repository with `https://github.com/LyreStudio/business-frontpage.git`, or download the ZIP from the marketplace website, extract it and add the folder. Older Lyre releases can browse and clone source; a new installer recipe requires an app update.

## Change it

Edit the HTML pages, `css/styles.css` and `js/scripts.js` directly. Refresh your preview after saving. Public files are listed in `public-files.json`; add a new file there before serving it locally. Original Pug/SCSS and build tooling remain at the pinned upstream link above.

This is a static website/UI template with sample content. Forms never send or save information; account pages do not authenticate; product controls do not provide checkout or inventory. Connect your own services before publishing. Versioned third-party CDNs provide Bootstrap, icons, fonts and optional UI libraries, so those enhancements need internet access. No SB Forms service is called. See [THIRD-PARTY.md](THIRD-PARTY.md) for rights and dependencies.

[Design](DESIGN.md) · [Agent guide](AGENTS.md) · [Validation](VALIDATION.md) · [Provenance](TEMPLATE.json)
