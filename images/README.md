# Images

This folder contains all image assets used across the Rod N Roam documentation.

## Folder Structure

```
images/
├── logo/           # App name logo and branding assets
├── screenshots/    # App screenshots (e.g. onboarding, map view, catch log)
└── roadmap/        # Roadmap infographic and feature timeline assets
```

## Guidelines

- **logo/** – Place the Rod N Roam app icon and wordmark files here (PNG, SVG, etc.).
- **screenshots/** – Add in-app screenshots that illustrate features or walkthrough steps. Name files descriptively, e.g. `home-screen.png`, `catch-log.png`.
- **roadmap/** – Store the roadmap infographic(s) here, e.g. `roadmap-2025.png`.

Use relative paths when referencing these images in documentation, for example:

```markdown
![Rod N Roam Logo](../images/logo/logo.png)
![Home Screen](../images/screenshots/home-screen.png)
![Roadmap](../images/roadmap/roadmap-2025.png)
```
