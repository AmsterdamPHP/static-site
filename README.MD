# static-site

## TODO

- [ ] Extract useful html components from the big index and blog templates to partials
- [ ] Determine site contents / pages
  - Ideas:
    - Home
    - Contact form for speakers
    - Contact form for sponsors/venues
    - Merch
    - Code of Conduct (probably wise to keep)
  - Brainstorming:
    - Ask the expert <-- just an idea because this year we've been contacted twice by someone that wanted to get in touch with a php developer for a small request/job
    - Learning resources? <-- to have something for juniors (who might never see the site)
- [ ] Design homepage.
  - Ideas: 
    - "Longest running PHP user group in the Netherlands"
    - First upcoming meetup as full-width card at the top
    - last 5 meetups as cards underneath
    - CTA Sponsor us somewhere
    - CTA Signup as speaker somewhere
    - Our mission statement at the bottom (like on current site)

## Documentation

Statically generated AmsterdamPHP site

This project uses [Jigsaw](https://jigsaw.tighten.com/docs/installation/) as static site generator.
It uses Blade templates, Markdown content and Tailwind CSS. 
Jigsaw also provides a CLI tool for building and serving the static site located at `vendor/bin/jigsaw`.

#### Ghostwind

In this project we copied the style of Ghostwind, a tailwind theme based on the popular Ghost Caspar layout.

## Setup

```
composer install
npm install
```

## Run

Start php server
```
vendor/bin/jigsaw serve
```

Compile the assets and watch for changes
```
npm run watch
```

## Deploy

TBD
