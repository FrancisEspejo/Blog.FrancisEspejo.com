# blog.francisespejo.com

![astro](https://img.shields.io/badge/built%20with-Astro-BC52EE)
![pages](https://img.shields.io/badge/hosted%20on-GitHub%20Pages-222)
![license](https://img.shields.io/badge/license-MIT-green)

My blog. Manuals, reviews, opinions and whatever else is worth writing down.

**[blog.francisespejo.com](https://blog.francisespejo.com)**

## What goes here

It is new, so it is still filling up. The plan is roughly this.

- **Manuals and how-tos**, the kind I write after solving something the hard way and not wanting to solve it twice
- **Reviews** of tools, services and hardware I actually use
- **Opinions**, mostly around security, systems and privacy
- **Notes**, shorter pieces that do not need a full article

Everything is written and reviewed by me. No generative AI. Bilingual, Spanish
and English, with a language switch in the header.

## Stack

Built with [Astro](https://astro.build), which suits a blog well. Content lives
in markdown, Astro renders it to static HTML at build time, and the browser gets
almost no JavaScript.

- Astro for the content pipeline and templating
- TypeScript for config and components
- Plain CSS, no framework
- Base theme: [Zahit](https://github.com/piyushmehta/zahit-astro) (MIT), heavily adjusted

## Hosting and deploys

GitHub Pages, deployed by GitHub Actions. Every push to `main` triggers the
workflow in `.github/workflows`, which builds the site and publishes it. The
custom domain sits in `public/CNAME` and the DNS lives in Cloudflare.

No server, no database, nothing to patch. A static site is one less thing that
can be attacked while I am asleep.

## Running it locally

```bash
git clone https://github.com/FrancisEspejo/Blog.FrancisEspejo.com.git
cd Blog.FrancisEspejo.com
npm install
npm run dev
```

Then open `http://localhost:4321`.

To check what will actually be deployed.

```bash
npm run build
npm run preview
```

## Writing a post

Posts are markdown files under `src/content/blog/`, split by language into `es/`
and `en/`. Add the file, fill in the frontmatter, push, and the workflow does the
rest.

## Related

- [francisespejo.com](https://francisespejo.com) is my landing page
- [domainwalk](https://github.com/FrancisEspejo/Domainwalk) is a CLI I wrote that audits the public surface of a domain

## License

Code is MIT, see [LICENSE](https://github.com/FrancisEspejo/Blog.FrancisEspejo.com/blob/main/LICENSE). The posts themselves are mine, so please link
rather than republish.
