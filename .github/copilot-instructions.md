# GitHub Copilot Instructions

This is a personal GitHub profile repository for Eren Mente, showcasing projects, skills, and GitHub statistics.

## Repository Purpose

This repository serves as:
- GitHub profile README (displayed on the profile page)
- Portfolio showcase with project links
- GitHub statistics and activity visualization
- Personal branding and professional presence

## Technology Stack

- **Markup**: Markdown for README content
- **Languages**: Java, JavaScript, HTML5, CSS3
- **Projects**: Full-stack web applications
- **Hosting**: GitHub Pages
- **Themes**: Tokyo Night color scheme

## Code Style Guidelines

### Markdown
- Use proper heading hierarchy (# for main title, ## for sections)
- Center-align badges and images using `<div align="center">` tags
- Use shields.io badges with consistent styling (`style=for-the-badge`)
- Maintain Turkish language for content (profile is in Turkish)
- Keep formatting consistent with existing structure

### General Practices
- Maintain visual consistency with the Tokyo Night theme
- Use semantic and descriptive section headers with emojis
- Keep URLs and links up to date
- Ensure all external resources (badges, graphs, images) are accessible
- Use responsive image sizing with height constraints

## Content Guidelines

- **Language**: Primary language is Turkish (Türkçe)
- **Tone**: Professional yet approachable
- **Focus**: Software engineering, web development, learning journey
- **Projects**: Highlight Java and JavaScript projects with live demos

## Common Tasks

### Updating Profile Statistics
- GitHub stats are pulled from external APIs (vercel.app)
- Activity graphs use tokyo-night theme
- Contribution snake animation is generated from output/github-contribution-grid-snake-dark.svg

### Adding New Projects
- Include project name, description, and live demo link
- Use consistent emoji prefixes (🍔, 📚, 💼, etc.)
- Format: `### [Project Name](github-link)` followed by description and demo link

### Maintaining Badges
- Use consistent badge style: `for-the-badge`
- Colors should align with Tokyo Night theme
- Include relevant technology logos

## Important Notes

- This is a profile README, not a project repository
- Changes here directly affect the GitHub profile appearance
- Test badge URLs and external resources before committing
- Keep content concise and visually appealing
- Ensure all links are functional

## External Dependencies

- GitHub README Stats API: github-readme-stats.vercel.app
- Profile Summary Cards: github-profile-summary-cards.vercel.app
- Activity Graph: github-readme-activity-graph.vercel.app
- Typing SVG: readme-typing-svg.herokuapp.com
- Visitor Badge: api.visitorbadge.io
- Shields.io for badges

## Workflow Information

The repository includes GitHub Actions workflows:
- `main.yml`: Main workflow
- `snake.yml`: Generates contribution snake animation

When making changes, ensure compatibility with these workflows.
