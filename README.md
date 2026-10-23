# Adam Pluguez — portfolio

The static site served at **adam-pluguez-portfolio.adaplu.chatgpt.site**.

## What this is

A snapshot of the published site, captured from the live build and turned into plain static files:

```
index.html                     the page
assets/index-D03ekufT.css      its stylesheet, unchanged
images/                        portrait and Quiz Royale screenshots
resume/Adam_Pluguez_Resume.pdf
```

No build step and no JavaScript. The original was rendered by a React/Vite app, and the published page
carried a serialized copy of its own markup for hydration plus a client bundle. Nothing on the page needs
them — there are no buttons and no forms, and the eleven expanding sections are native `<details>` — so the
scripts were dropped and what remains is the rendered HTML.

## How it relates to the ChatGPT project

This is a **fork, not the source**. The site is authored in a ChatGPT project and published to
`*.chatgpt.site`; this repository is a copy taken from the published output. Edit in one place or the other,
not both, or they will drift.

## Changes applied here

The published page already had Reseller All-in-One removed, ClickDungeon2 renamed to ClickDungeon, its
repository link pointed at `github.com/adaPlu/Click`, and the project numbers corrected to 01–10. One edit
was still outstanding and is applied in this copy:

- A **Screenshots & concept art** link on the ClickDungeon card, beside the repository link.

That link currently points at a private gallery page. It has to be shared publicly before visitors can open it.

## Serving it

Any static host. For GitHub Pages the repository must be public, and Pages should serve from the repository
root on the default branch.

## License

Original project source code is licensed under the [MIT License](LICENSE). The separate [LICENSE-SCOPE.md](LICENSE-SCOPE.md) clarifies exclusions for personal or third-party materials.
