# RIDE project page

Static project page for **RIDE: Relocalization-Informed Depth Estimation**, prepared for a public personal Pages release and a later clean anonymous mirror.

## Preview locally

Serve the `docs` directory with any static file server. For example:

```powershell
python -m http.server 8000 --directory docs
```

Then open `http://localhost:8000`.

## Publish with GitHub Pages

1. Create a clean, dedicated GitHub repository. Do not initialize the whole `RIDE` workspace or reuse the Overleaf repository.
2. Add only the contents of this `ride-project-page` directory.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/docs` folder, then save.

The planned personal project page is
`https://lian-jiarong.github.io/RIDE-Relocalization-Informed-Depth-Estimation/`.

The canonical, Open Graph, and X image URLs in `docs/index.html` currently target
that personal project-page address.

## Public page and anonymous submission

- The personal Pages site is intentionally public and identifies its owner through the URL and repository history.
- IEEE RAS permits public preprints, but a double-anonymous submission must not link to a personal-account URL that directly identifies the authors.
- For submission, make a separate anonymous mirror with clean ownership and history, or use `anonymous.4open.science`; link only that anonymous URL from the review manuscript.
- Before creating the anonymous mirror, remove or replace the personal canonical, `og:url`, `og:image`, and `twitter:image` values, and change the visible `Project page` status if desired.
- Before any public release, confirm participant consent and re-check every visible frame, figure, filename, and media metadata.
- The web videos are separate derivatives: 1920×1080, 25 fps H.264, silent audio removed, metadata stripped, and desktop chrome cropped. The visible face region in the Office sequence is blurred. The source videos are unchanged.

## Media

- `docs/assets/media/ride-demo.mp4`: optimized Office demo, approximately 15 MB.
- `docs/assets/media/ride-demo-poster.jpg`: Office poster frame.
- `docs/assets/media/ride-demo-lobby.mp4`: optimized Lobby demo, approximately 10 MB.
- `docs/assets/media/ride-demo-lobby-poster.jpg`: Lobby poster frame.
- `docs/assets/figures/`: selected manuscript figures and focused method diagrams.

## Claims boundary

The page intentionally avoids “state of the art,” “real-time,” and “first” claims. Reported numbers are scoped to the evaluated benchmark and reproduce the current manuscript table.
