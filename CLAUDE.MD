# Social Contract Research Centre - Geneva

## Project Overview

This is the website for the Social Contract Research Centre (SCRC), an academic research organization based in Geneva. The site is a bilingual (English/French) static website showcasing the centre's research, tools, and activities related to social contract theory and its modern applications.

## Project Structure

```
.
├── index.html              # Main landing page (English)
├── index-fr.html          # French version of landing page
├── index-bilingual.html   # Bilingual version with language toggle
├── index-updated.html     # Updated version (work in progress)
├── research.html          # Research page with accordion sections
├── research-fr.html       # French version of research page
├── tools.html             # Tools and resources page
├── tools-fr.html          # French version of tools page
├── scrc-about-page.html   # About page
├── logo.svg               # SCRC logo
├── files/                 # Static assets and resources
└── scrc-about-page_files/ # Assets for about page
```

## Technology Stack

- Pure HTML/CSS (no build process)
- Custom CSS with responsive design
- Google Fonts: EB Garamond and Inter
- Static site deployment

## Design System

### Colors
- Background: `#F8F6F1` (warm off-white)
- Primary text: `#2D2D2D` (dark gray)
- Primary brand: `#1C3A54` (deep blue)
- Accents: `#C17B5C` (warm terracotta)
- Borders: `#d0cdc4` (light gray)

### Typography
- Headings: 'EB Garamond' (serif)
- Body text: 'Inter' (sans-serif)
- Academic, professional aesthetic

### Layout
- Max width: 1200px
- Responsive padding: 60px (desktop)
- Mobile-first responsive design

## Key Features

1. **Bilingual Support**: Full English and French versions of all content
2. **Research Section**: Accordion-style interface for research topics
3. **Tools Section**: Interactive resources and references
4. **Logo**: Custom SVG seal with three interlocking circles
5. **Clean Academic Design**: Professional, readable, scholarly appearance

## Recent Changes

Based on git history:
- Updated diagrams (current vs future)
- Changed Wikipedia references to "Grokipedia"
- Added logo version 1
- Fixed research page links
- Added research pages with accordion functionality
- Implemented bilingual support with improved design
- Updated contact information (address and email)

## Development Guidelines

### When Making Changes

1. **Maintain Bilingual Consistency**: Always update both English and French versions
2. **Preserve Design System**: Use existing color palette and typography
3. **Test Responsiveness**: Ensure changes work on mobile and desktop
4. **Keep Accessibility**: Maintain semantic HTML and proper contrast ratios
5. **Static Assets**: Place new files in the `files/` directory

### File Naming Conventions

- English: `filename.html`
- French: `filename-fr.html`
- Experimental: `filename-updated.html` or `filename-bilingual.html`

### Code Style

- Inline CSS in `<style>` tags (no external stylesheets currently)
- Use consistent indentation (4 spaces)
- Semantic HTML5 elements
- Mobile-first media queries

## Common Tasks

### Adding a New Page

1. Create English version: `newpage.html`
2. Create French version: `newpage-fr.html`
3. Add navigation links to both versions
4. Update language toggle links
5. Follow existing page structure and styling

### Updating Content

- Main content sections use semantic HTML
- Hero sections, feature cards, and text blocks follow established patterns
- Maintain the academic tone and professional presentation

### Styling Updates

- All styles are currently inline in each HTML file
- Update the `<style>` section in both English and French versions
- Consider extracting to external CSS if styles become too complex

## Contact Information

- Location: Geneva, Switzerland
- Organization: Social Contract Research Centre
- Check HTML files for current contact details

## Notes for AI Assistants

- This is an academic/research website requiring professional, scholarly tone
- All content should maintain consistency across language versions
- Design emphasizes readability and accessibility for academic audiences
- No backend or dynamic functionality - purely static HTML/CSS
- When suggesting changes, always consider impact on both language versions
