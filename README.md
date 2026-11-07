# Omar Dawoud — Personal Portfolio

A personal portfolio website introducing Omar Dawoud, showcasing selected web projects, and featuring **Tech & Taps**, a technology channel about computer science and practical tech topics.

## Live site

[View the portfolio](https://omardawoud54.github.io/my-portfolio/)

## What’s on the site

- **Welcome section** with a looping video background and portfolio navigation.
- **Tech & Taps** channel overview, social links, and a selection of embedded YouTube videos.
- **Featured projects** with preview images, descriptions, live demos, and GitHub repositories.
- **About section** describing Omar and his current technical toolkit.
- **Contact links** for Facebook, Instagram, and email.

## Built with

- HTML for the page structure and content.
- SCSS for modular styling, compiled to the minified stylesheet used by the page.
- Vanilla JavaScript embedded in `index.html` to render the YouTube video cards.

YouTube embeds and the Google Font are loaded from their respective services, so those features require an internet connection.

## Run locally

No package installation or build step is required. Clone or download the repository, then open `index.html` in a browser. For local development, you can also serve the repository with any static-file server.

## Repository structure

```text
├── assets/                  # Profile, project, social, and background media
├── css/
│   └── style.min.css        # Stylesheet loaded by index.html
├── scss/
│   ├── _about.scss          # About section
│   ├── _content.scss        # Tech & Taps and video content
│   ├── _header.scss         # Welcome section and background video
│   ├── _navbar.scss         # Navigation
│   ├── _projects.scss       # Featured project cards
│   └── style.scss           # SCSS entry point
├── index.html               # Portfolio page and video-card script
├── LICENSE
└── README.md
```

## Featured projects

- [Blog Post Layout Website](https://omardawoud54.github.io/Blog-Post/) · [Source code](https://github.com/omardawoud54/Blog-Post)
- [Neon Loading Animation](https://omardawoud54.github.io/loading-animation/) · [Source code](https://github.com/omardawoud54/loading-animation)
- [Writings.dev Website Layout](https://omardawoud54.github.io/writings-dev/) · [Source code](https://github.com/omardawoud54/writings-dev)

## License

This project is available under the [MIT License](LICENSE).
