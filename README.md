# Mintlify page templates

This repository is a collection of ready-to-use page layouts for [Mintlify](https://mintlify.com) documentation sites. Each template is self-contained: you can copy the pieces you need into your own project and adapt the copy, links, and styling to match your brand.

Templates are meant to be mixed and matched. Treat them as starting points for custom pages, hero sections, card grids, and supporting assets rather than a single app you install end-to-end.

## How to use a template

1. Open the folder for the template you want (see below).
2. Copy the **MDX** (and any **CSS** or **JavaScript** files) into your Mintlify content or static paths, following your project’s structure.
3. Merge **configuration** carefully: colors, logo paths, favicon, and navigation in `docs.json` should align with your existing site. Do not overwrite your whole `docs.json` unless you intend to replace it. The `docs.json` files bundled with these templates are intentionally minimal so the example stays easy to read; they are not a full production navigation or settings setup.
4. If the template ships a `style.css`, add it to your documentation repository (alongside your MDX). Mintlify loads CSS files from your repo, so those rules and class names apply in your project instantly once loaded. See [Custom scripts](https://mintlify.com/docs/settings/custom-scripts) in the Mintlify docs for details, including how `style.css` works and which UI selectors are safe to target.
5. Replace placeholder **logo**, **favicon**, and **copy** with your own.

Always check the [Mintlify documentation](https://mintlify.com/docs) for the latest options for custom pages, components, and theming.

## Templates in this repo

| Folder | Description |
|--------|-------------|
| [`help-center-homepage/`](./help-center-homepage/) | A help-center style landing page: centered hero, search entry, grids of cards for suggested category pages and articles. Includes companion `style.css` for card layout, `search.js` for opening Mintlify search from a custom trigger, and example `docs.json` plus logo and favicon assets. |

More templates will be added over time as additional directories at the repository root.

## Contributing

If you open a pull request to add a new template, it should live in its own folder under the root directory of this repository. Keep filenames predictable (`index.mdx`, `style.css`, etc. when needed), and include it in the table above so others can discover it quickly.
