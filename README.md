# ReCAT Project Website

Project page for **ReCAT: Remember, Count, And Time: Structured Recurrent Memory for Robot Manipulation**


The page is `index.html`. It uses the Bulma / Font Awesome assets in [`static/`](static/). The ReCAT figures
are `static/images/recat_*`, taken from the paper PDF.

## Local preview

```bash
python3 -m http.server 8000
# http://localhost:8000/index.html
```

## TODO before publishing

- Check author affiliations (Mizrakli and Hatab are currently listed under KIT IRL).
- Fill in the **Paper**, **arXiv** and **Code** links in `index.html` (they currently use `href="#"` and are greyed out).
- Replace the video placeholder (`<div class="video-slot">`) with the supplementary video.
- Update the BibTeX once the arXiv ID is known.
- Set up a new GitHub repo / Pages site for this folder (it is separate from the DAM-VLA repo).

## Template credit

Built on the [Nerfies](https://github.com/nerfies/nerfies.github.io) project page template, licensed
under [CC BY-SA 4.0](http://creativecommons.org/licenses/by-sa/4.0/).
