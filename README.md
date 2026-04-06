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
├── eta_unified.html        # Full ETA assessment (HW/SW/DS/GC modes)
├── eta-seeds.html          # Seeds & Germplasm assessment (NEW)
├── license-engine.html     # Polycentric License Engine (NEW)
├── eta-comparison.html     # Communications tools comparison
├── eta-data-comparison.html # Data collection tools comparison
├── eta-scorecard.html      # Quick scoring view
├── submit-tool.html        # Submit new tools for review
├── about.html              # Framework explanation
├── styles.css              # Shared styles
└── README.md               # This file
```

## Features

### Core Assessment Tools
- **ETA Unified**: Run full assessments for Hardware, Software, Datasets, and Guardian Connector modes
- **Needs Assessment**: Step-by-step tool finder based on community needs
- **Matrix View**: Filter and compare all tools by CEI fit, phone type, cost

### NEW: Seeds & Germplasm Assessment
- Assess seed and genetic material sharing practices
- Based on the **Wheat Workers' Code of Ethics** (1994)
- Integrates **CARE Principles** for Indigenous Data Sovereignty
- 20 questions across 4 pillars: Rights & Transparency, Distribution Controls, Benefit Sharing, Special Use Conditions
- Derived from Guardian Connector model with attribution

### NEW: Polycentric License Engine
- Find the right license for software, data, hardware, or **seeds/germplasm**
- Build custom polycentric agreements with conditional use blocks
- Seeds category includes blocks derived from Wheat Workers' Code:
  - Originator Rights Retained (§1)
  - Secondary Distribution Restriction (§2)
  - Regional/International Trials (§3a)
  - Cultivar Release Restriction (§3b)
  - Backcrossing, Mutation Breeding, Gene Transfer rules (§3e-h)
  - Trial Material Seed Increase rules (§4)
- CARE Principles integration for indigenous data sovereignty

### Other Features
- **Tool Comparison**: Side-by-side analysis of communications tools
- **Submit Tool**: Community contribution form
- **Responsive Design**: Works on mobile, tablet, and desktop
- **Offline Capable**: No backend required, works locally

## Framework References

### Seeds & Germplasm Assessment
- **Wheat Workers' Code of Ethics** — National Wheat Improvement Committee (1994)
  - Source: [USDA ARS](https://www.ars.usda.gov/ARSUserFiles/30421000/wheatcode.html)
- **CARE Principles** — Collective Benefit, Authority to Control, Responsibility, Ethics
  - Source: [Global Indigenous Data Alliance](https://www.gida-global.org/care)
- **Guardian Connector** — Indigenous data sovereignty criteria
  - Source: [Guardian Connector Docs](https://docs.guardianconnector.net)
- **Ethical Infrastructure at TLI** — The Land Institute's Perennial Cultures Lab

### License Engine
- **OpenTEAM Polycentric License Engine** — Original framework
- **Open Source Seed Initiative (OSSI)** — Freed seed model
- **ITPGRFA** — International Treaty on Plant Genetic Resources for Food and Agriculture

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
- Connecting to Supabase for live data (see ETA_Implementation_Guide.md)

## License

This work is licensed under Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0).

## Communities

- **OpenTEAM** — openteam.community
- **Farm Hack** — farmhack.org
- **GIAA** — Grassroots Innovation Assembly for Agroecology
- **The Land Institute** — landinstitute.org

## Contact

eta@openteam.community
