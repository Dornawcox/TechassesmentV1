# Ethical Technology Assessment (ETA) Site

A static website for evaluating agricultural digital tools through a Commons-Enabling Infrastructure lens.

## Quick Start

1. Download and extract the ZIP file
2. Open `index.html` in any web browser
3. No server required — works entirely offline

## Hosting on GitHub Pages

1. Create a new GitHub repository
2. Upload all files to the repository root
3. Go to Settings → Pages
4. Set source to "main" branch and "/" (root)
5. Your site will be available at `https://yourusername.github.io/repository-name/`

## Site Structure

```
eta-site/
├── index.html              # Home page
├── needs-assessment.html   # Guided tool finder + matrix view
├── assessment-matrix.html  # Detailed tool assessments
├── submit-tool.html        # Submit new tools for review
├── about.html              # Framework explanation
├── styles.css              # Shared styles
└── README.md               # This file
```

## Features

- **Needs Assessment**: Step-by-step tool finder based on community needs
- **Matrix View**: Filter and compare all tools by CEI fit, phone type, cost
- **Tool Assessments**: Detailed ETA scores with Entry Gates and Scored Dimensions
- **Submit Tool**: Community contribution form
- **Responsive Design**: Works on mobile, tablet, and desktop
- **Offline Capable**: No backend required, works locally

## Tools Assessed

| Tool | ETA Score | CEI Fit |
|------|-----------|---------|
| farmOS | 92/100 | High |
| LiteFarm | 88/100 | High |
| KAOP | 78/100 | High |
| Kuza | 74/100 | Medium-High |
| Digital Green | 72/100 | Medium-High |
| iShamba | 68/100 | Medium |
| FarmerChat | 65/100 | Medium |
| ShambaPro | 58/100 | Medium |
| GSuite | 45/100 | Low |

## Customization

The site uses Tailwind CSS via CDN. To customize:

1. Edit the HTML files directly
2. Modify `styles.css` for shared styles
3. Tool data is embedded in JavaScript within each page

For a production deployment, consider:
- Replacing Tailwind CDN with compiled CSS
- Adding a backend for tool submissions
- Implementing search/filter persistence

## License

This work is licensed under Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0).

## Communities

- **OpenTEAM** — openteam.community
- **Farm Hack** — farmhack.org
- **GIAA** — Grassroots Innovation Assembly for Agroecology

## Contact

eta@openteam.community
