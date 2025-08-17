# VibeGuide AI Documentation

Your AI-Powered Cultural Compass for Confident Global Travel

## About

VibeGuide AI transforms the way you experience different cultures by providing real-time, AI-powered cultural intelligence. Never feel lost or uncertain in a new cultural context again.

## Documentation

This repository contains the complete documentation for VibeGuide AI, built with MkDocs and deployed automatically to GitHub Pages.

### Local Development

To run the documentation locally:

```bash
# Install dependencies
pip install -r requirements.txt

# Serve locally with hot reload
mkdocs serve

# Build static site
mkdocs build
```

The documentation will be available at `http://localhost:8000`

### Deployment

The documentation is automatically deployed to GitHub Pages via GitHub Actions whenever changes are pushed to the `main` branch.

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test locally with `mkdocs serve`
5. Submit a pull request

## Structure

```
docs/
├── index.md                    # Homepage
├── getting-started.md          # Getting started guide
├── features/                   # Feature documentation
│   ├── cultural-intelligence.md
│   └── real-time-guidance.md
└── support/                    # Support documentation
    └── faq.md
```

## License

© 2024 VibeGuide AI. All rights reserved.