# GitHub Profile Setup Guide

## Résumé-derived positioning

- Primary identity: AI/ML and full-stack developer.
- Strongest domains: computer vision, NLP, frontend engineering, backend API development, and database-backed applications.
- Strongest projects: Cattle Breed Prediction System, Smart AI Notes Summarizer, and Gamified Learning Platform.
- Most valuable experience: MERN Stack Developer at Tekriq Technologies and Frontend Intern at Pranav Techy.
- Main visual emphasis: project architecture, applied technology groups, internship contributions, offline-first engineering, and technical leadership.

## Repository structure

```text
AshwathNagarajan/
├── README.md
├── SETUP.md
├── assets/
│   ├── profile-banner-light.svg
│   ├── profile-banner-dark.svg
│   ├── cattle-breed-preview.png
│   ├── notes-summarizer-preview.png
│   └── gamified-learning-preview.png
└── .github/
    └── workflows/
        └── contribution-snake.yml
```

## Placeholders to replace

- `YOUR_PORTFOLIO_URL`
- `YOUR_RESUME_URL`
- `YOUR_CATTLE_BREED_REPOSITORY_URL`
- `YOUR_CATTLE_BREED_DOCUMENTATION_URL`
- `YOUR_NOTES_SUMMARIZER_REPOSITORY_URL`
- `YOUR_NOTES_SUMMARIZER_DEMO_URL`
- `YOUR_GAMIFIED_LEARNING_REPOSITORY_URL`
- `YOUR_GAMIFIED_LEARNING_DEMO_URL`
- `YOUR_CERTIFICATIONS_URL`
- `YOUR_ACHIEVEMENTS_URL`
- `YOUR_CURRENT_COLLABORATION_INTERESTS`
- `YOUR_CODING_PROFILE_URL`

## Custom asset prompts

### Light profile banner

- File: `assets/profile-banner-light.svg`
- Recommended size: 1600 × 420 px
- Prompt: Create a clean professional GitHub profile banner for Ashwath Nagarajan, an AI/ML and full-stack developer. Use a light neutral background, subtle navy and slate geometric data-flow lines, small abstract nodes representing computer vision, NLP, APIs, databases, and React interfaces. Place the name “Ashwath Nagarajan” prominently and the subtitle “AI/ML and Full-Stack Developer.” Minimal, technical, recruiter-friendly, flat vector SVG, no human portrait, no emojis, no mascots, no excessive gradients, wide 1600:420 composition.

### Dark profile banner

- File: `assets/profile-banner-dark.svg`
- Recommended size: 1600 × 420 px
- Prompt: Create a dark-mode companion to a professional GitHub profile banner for Ashwath Nagarajan, an AI/ML and full-stack developer. Use a deep charcoal background, restrained blue and cyan data-flow lines, small abstract nodes representing computer vision, NLP, APIs, databases, and React interfaces. Place the name “Ashwath Nagarajan” prominently and the subtitle “AI/ML and Full-Stack Developer.” Minimal, technical, recruiter-friendly, flat vector SVG, no human portrait, no emojis, no mascots, no excessive glow, wide 1600:420 composition.

### Cattle Breed Prediction preview

- File: `assets/cattle-breed-preview.png`
- Recommended size: 1200 × 675 px
- Prompt: Professional software project cover showing a clean cattle image detection interface with a precise bounding box, breed prediction result panel, FastAPI processing flow, PostgreSQL data card, and a restrained modern React dashboard. Technical portfolio screenshot style, realistic interface, no fabricated performance metrics, no logos beyond ordinary technology marks, 16:9.

### Smart AI Notes Summarizer preview

- File: `assets/notes-summarizer-preview.png`
- Recommended size: 1200 × 675 px
- Prompt: Professional software project cover for an offline AI notes summarizer. Show a clean split interface with source notes, concise generated summary, quiz cards, and small image and audio learning modules. Emphasize local processing and privacy without fake statistics. Modern React application aesthetic, restrained colors, 16:9.

### Gamified Learning Platform preview

- File: `assets/gamified-learning-preview.png`
- Recommended size: 1200 × 675 px
- Prompt: Professional educational application cover for an offline gamified learning platform designed for rural school learners and low-spec devices. Show lightweight SVG-based lesson interactions, a chapter map, progress indicators, and an offline status element. Accessible, friendly but not childish, clean web interface, no fake metrics, 16:9.

## Publishing steps

1. Create a public repository named exactly `AshwathNagarajan`.
2. Copy `README.md`, `assets/`, and `.github/` into the repository.
3. Replace all placeholders listed above.
4. Add the two banner SVG files or remove the banner `<picture>` block temporarily.
5. Commit and push to the `main` branch.
6. Open the Actions tab and manually run **Generate Contribution Snake** once.
7. Confirm that the `output` branch contains both generated SVG files.
8. Test the profile in GitHub light and dark modes and on a mobile-width browser.

## Quality audit

- No emojis are used.
- No Font Awesome JavaScript or unsupported scripting is required.
- Icons are loaded through GitHub-compatible image sources.
- Résumé facts have not been expanded into unsupported claims.
- Phone number and residential details are excluded.
- Images include meaningful `alt` text.
- Light and dark variants are provided where practical.
- Mermaid diagrams use standard GitHub-supported syntax.
- HTML tags are closed.
- Layouts use compact tables that degrade acceptably on narrow screens.
- Technologies are grouped and not intentionally duplicated within the main stack.
- Analytics are dynamic and are not presented as fixed résumé claims.
- The contribution animation is clearly optional.
