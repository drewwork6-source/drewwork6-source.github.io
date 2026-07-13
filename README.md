# Drew Seidel — Landing Page

**🔗 Live:** https://drewwork6-source.github.io/

The main entry point for outreach — a traditional scrolling landing page (hero, work grid, skills,
contact) with a featured callout linking out to [the maze](https://drewwork6-source.github.io/labyrinth-portfolio/),
an optional interactive 3D walkthrough experience.

## Sections

- **Hero** — headline, summary, and CTAs (View My Work / Walk the Maze / Download Resume)
- **The Experience** — a callout card linking to the labyrinth-portfolio maze as an optional detour
- **My Work** — grid of every live project: client & showcase websites, plus apps & tools
- **Skills** — tools & stack chips
- **Contact** — email, phone, GitHub

## Adding new projects

Open `index.html` and look for the HTML comments:

```html
<!-- ADD NEW WEBSITE PROJECT CARDS ABOVE THIS LINE. -->
<!-- ADD NEW APP/TOOL PROJECT CARDS ABOVE THIS LINE. -->
```

Copy one of the existing `<a class="reveal card-hover ...">` card blocks right above the relevant
comment, swap in the new `href`, pick any `.grad-1` through `.grad-11` class for the color header,
and update the badge text, title, and description.

## Tech Stack

- HTML + Tailwind CSS (CDN)
- Vanilla JS (IntersectionObserver scroll reveals)
- No build step — static file, deployable anywhere

## Running Locally

```bash
open index.html
# or
python -m http.server 8000
```

## Status

🟢 Live, hosted via GitHub Pages (user page) from the `main` branch.
