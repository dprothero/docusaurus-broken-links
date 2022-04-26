# Error Reproduction Repo

A repro repo, if you will.

## Steps used to create this repo

1. Ran `npx create-docusaurus@latest my-website classic`
2. `cd my-website`
3. Added the [docs/tutorial-basics/quickstart/quickstart.md](docs/tutorial-basics/quickstart/quickstart.md) file.
4. Added a link to [docs/intro.md](docs/intro.md) to the newly created file.
5. Ran `npm run build`

This produces the following output:

```text
[ERROR] Unable to build website for locale en.
[ERROR] Error: Docusaurus found broken links!

Please check the pages of your site in the list below, and make sure you don't reference any path that does not exist.
Note: it's possible to ignore broken links with the 'onBrokenLinks' Docusaurus configuration, and let the build pass.

Exhaustive list of all broken links found:

- On source page path = /docs/intro:
   -> linking to /docs/tutorial-basics/quickstart/quickstart.md
```
