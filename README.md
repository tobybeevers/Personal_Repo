# Toby Beevers | Personal Website

A static personal website built with HTML and CSS, hosted via GitHub Pages.

This repo captures my personal and professional journey, including:
- key milestones in my career
- personal development highlights
- links to my profiles and resources
- blog posts about projects and experiences

## Live Site

You can view the website here:

- **GitHub Pages:** https://tobebeevers.github.io/My_Personal_Repo/

## Tech Stack

- HTML5
- CSS3
- Font Awesome (icons)

## Project Structure

```text
.
├── index.html
├── my_early_years.html
├── career_change.html
├── personal_development.html
├── my_links.html
├── my_blog.html
├── Blog-Posts/
│   ├── blog_AIML.html
│   ├── blog_CentralBilling.html
│   ├── blog_CareerChange.html
│   ├── blog_JupyterNotebook.html
│   ├── blog_MyCSR.html
│   ├── blog_O365Migrations.html
│   ├── blog_PowerBI.html
│   └── blog_template.html
├── css/
│   ├── containers.css
│   ├── styles.css
│   └── timeline.css
└── library/
    ├── images
    ├── favicons
    └── CV files
```

## Run Locally

Because this is a static site, you can open `index.html` directly in your browser.

For a better local development experience (recommended), run a simple local server from the repository root:

```bash
python -m http.server 8000
```

Then open:

- `http://localhost:8000`

## Maintenance Notes

- Keep global layout and component styles in `css/styles.css` and `css/containers.css`.
- Use `css/timeline.css` for timeline-specific styling.
- Add new blog pages in `Blog-Posts/` and link them from `my_blog.html`.
- Store reusable media and document assets in `library/`.

## License

This project is licensed under the terms of the [LICENSE](LICENSE) file.
