# Mintlify page templates

This repository is a collection of ready-to-use page layouts for [Mintlify](https://mintlify.com) documentation sites. Each template is self-contained: you can copy the pieces you need into your own project and adapt the copy, links, and styling to match your brand.

Templates are meant to be mixed and matched. Treat them as starting points for custom pages, hero sections, card grids, and supporting assets rather than a single app you install end-to-end.

## How to use a template

There are two ways to start a new Mintlify project from one of these templates:

1. **Select it during onboarding.** When you create a new docs site through [Mintlify onboarding](https://dashboard.mintlify.com), pick the template you want and Mintlify will scaffold a project from it.
2. **Use the Mintlify CLI.** Install and set up the CLI by following the [CLI documentation](https://www.mintlify.com/docs/cli/install), then create a new project using the `--template` flag with the template's directory name:

   ```bash
   mint new --template <template-name>
   ```

   For example, to start from the `help-center` template:

   ```bash
   mint new --template help-center
   ```

Always check the [Mintlify documentation](https://mintlify.com/docs) for the latest on components, themes, `docs.json` configuration, and the rest of the Mintlify platform.

## Templates in this repository

- **Help Center** ([source](./help-center/), [preview](https://help-center-starter.mintlify.app))

  A help-center style landing page: centered hero, search entry, and card grids for category pages and articles. Includes `style.css` for card layout, `search.js` for opening Mintlify search from a custom trigger, example section pages, and `docs.json` plus logo and favicon assets.
- **Knowledge Base** ([source](./knowledge-base/), [preview](https://knowledge-base-starter.mintlify.app))

  An internal knowledge base including a landing page with department cards, plus example content sections for onboarding, different departments, and policies. Includes `style.css` for table-of-contents styling, a full multi-section navigation in `docs.json`, and logo and favicon assets.
- **Product Guide** ([source](./product-guide/), [preview](https://product-guide-starter.mintlify.app))

  A product guide site designed for multi-product documentation. Includes a landing page and product selector to switch between different product guides.
