# alyssaclark.org

Personal website for Alyssa Clark, impact consultant based in London.

**Live at [alyssaclark.org](https://alyssaclark.org)**

Plain HTML and CSS. Hosted on GitHub Pages.

## Stack

- Static HTML/CSS
- DM Serif Display + DM Sans (self-hosted)
- GitHub Pages + custom domain

## Structure

```
index.html          Homepage: intro, services, three most recent projects, about
services.html       Full service details
projects/index.html Project list (most recent first)
projects/*.html     Individual project pages
styles.css          All styling (colour variables at top)
fonts/              Self-hosted web fonts
images/            Portrait (homepage) and og-image.jpg (link previews)
yoga/               Standalone yoga page with its own stylesheet (yoga-base.css)
```

## Editing

All content lives directly in the HTML files. Look for the comment banners marking each section.

To add a project:

1. Copy an existing page in `projects/` and update the tags, title, client/year line and body.
2. Add an `<li class="project-item">` entry to `projects/index.html`, keeping the list in reverse chronological order.
3. Update the "Older/Newer" links at the bottom of the neighbouring project pages.
4. If it's one of the three newest, swap it into the "Recent projects" list on `index.html`.

To retheme, edit the CSS custom properties at the top of `styles.css`.

## License

Content is copyrighted. Code structure is free to reuse.
