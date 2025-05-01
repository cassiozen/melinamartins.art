# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Commands
- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build locally
- `npm run astro` - Run Astro CLI commands

## Code Style Guidelines
- Use tabs for indentation in Astro files
- Follow TypeScript strict mode rules (extends astro/tsconfigs/strict)
- Order imports alphabetically with built-ins first, then external, then internal
- Component names use PascalCase (e.g., HeroSection.astro)
- CSS uses kebab-case class names (e.g., hero-grid)
- CSS variables follow --prefix-name pattern
- Use CSS scoping within Astro components via <style> tags
- Type interfaces should use PascalCase and be defined at the top of components
- Add alt text to all images
- Media queries use min-width with mobile-first approach
- Keep components single-purpose and focused
- Use semantic HTML elements (section, header, footer, etc.)