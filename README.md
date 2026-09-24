# Digital Orth Masters

Static landing page for the Digital Orth Masters digital orthodontics course (Dr. Mohamed Hesham).

## Structure

```
index.html              the whole site (HTML + CSS + JS in one file)
assets/img/             article covers (SVG), curriculum module images, in-article figures
assets/video/           video testimonials (mp4) and their poster images
assets/papers/          26 research papers (PDF), one per article
.nojekyll               tells GitHub Pages to serve files as-is
```

## Deploying

Push to a GitHub repo, then enable Pages:
Settings -> Pages -> Source: "Deploy from a branch" -> Branch: `main` -> Folder: `/ (root)`.

`index.html` must stay in the repository root.

## Notes

- Videos use `preload="none"`, so nothing downloads until the visitor presses play.
- Article PDFs download only when the visitor clicks the download button in an article.
- Fonts load from Google Fonts; the logo and two photos load from Cloudinary. Everything else is local.
