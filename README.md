# Personal Portfolio

Portfolio site organized for readability and maintainability.

## Project Structure

```text
.
├── index.html
├── pages/
│   ├── home.html
│   ├── resume.html
│   ├── experience.html
│   ├── projects.html
│   ├── project-detail.html
│   └── contact.html
├── styles/
│   ├── home.css
│   ├── resume.css
│   ├── experience.css
│   ├── projects.css
│   ├── project-detail.css
│   └── contact.css
└── assets/
    ├── docs/
    │   └── emma-de-la-cruz-resume.pdf
    ├── images/
    │   ├── backgrounds/
    │   ├── branding/
    │   ├── decor/
    │   ├── icons/
    │   ├── portraits/
    │   ├── screenshots/
    │   │   ├── current/
    │   │   └── legacy/
    │   └── archive/
    └── archive/
```

## Naming Rules

- Use lowercase `kebab-case` for all files.
- Use descriptive names (`contact-bg.jpg`, `study-planner.png`).
- Avoid spaces, parentheses, and `copy` in filenames.

## Asset Rules

- Put active screenshots in `assets/images/screenshots/current/`.
- Put previous versions in `assets/images/screenshots/legacy/`.
- Put deprecated or unused files in `assets/images/archive/` or `assets/archive/`.

## Entry Point

- Open `index.html` from the project root.
