# Awards Portfolio Platform

A high-performance, interactive portfolio website showcasing projects and accomplishments with cutting-edge web technologies. This platform combines modern animation capabilities with responsive design to deliver an immersive user experience.

## Overview

The Awards Portfolio Platform is a sophisticated web application designed to present awards, projects, and professional stories with captivating animations and smooth interactions. Built for businesses and professionals who need to make a lasting digital impression.

## Key Features

- **Interactive Video Carousel**: Dynamic hero section with video switching and seamless transitions
- **3D Perspective Effects**: Advanced hover interactions with tilt and scale animations
- **Scroll-Based Animations**: Professional animations triggered by scroll position for engaging content reveal
- **Responsive Design**: Fully optimized for all device sizes from mobile to desktop
- **Performance Optimized**: Lightning-fast load times and smooth 60fps animations
- **Professional Sections**: 
  - Navigation bar with smooth scrolling
  - Hero showcase with video carousel
  - About section
  - Features display
  - Story timeline
  - Contact form
  - Footer navigation

## Technology Stack

### Why This Combination Excels

**React 19** → **Vite** → **Tailwind CSS** → **GSAP** provides an unbeatable combination for modern web applications:

- **React 19**: Component-based architecture enables reusable, maintainable code with optimal state management
- **Vite**: Next-generation build tool delivering instant server start and lightning-fast HMR (Hot Module Replacement), reducing development time significantly
- **Tailwind CSS 4**: Utility-first framework allows rapid UI development without context switching, while PostCSS integration ensures optimal CSS output
- **GSAP 3**: Industry-standard animation library enables pixel-perfect animations with ScrollTrigger plugin for scroll-driven effects
- **React Icons**: Lightweight, tree-shakeable icon library reducing bundle size while providing rich UI elements

This tech stack ensures:
- **Development Speed**: Vite's instant feedback loop accelerates iteration
- **Code Quality**: React's component model promotes clean, scalable architecture
- **Performance**: Tree-shaking, code splitting, and optimized builds result in minimal load times
- **Animation Excellence**: GSAP + ScrollTrigger provides professional-grade animations at 60fps
- **Maintainability**: Tailwind's utility classes and React components make codebase easy to update

## Installation

```bash
# Install dependencies
npm install

# Start development server (runs on http://localhost:5173)
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview

# Run ESLint for code quality checks
npm run lint
```

## Project Structure

```
src/
├── components/
│   ├── NavBar.jsx          # Navigation component
│   ├── Hero.jsx            # Hero section with video carousel
│   ├── About.jsx           # About section
│   ├── Features.jsx        # Features showcase
│   ├── Story.jsx           # Story timeline
│   ├── Contact.jsx         # Contact form
│   ├── Footer.jsx          # Footer navigation
│   ├── Button.jsx          # Reusable button component
│   ├── AnimatedTitle.jsx   # Animated title component
│   └── RoundedCorners.jsx  # UI utility component
├── App.jsx                 # Main application component
├── main.jsx                # React entry point
└── index.css               # Global styles
```

## Development

The project uses:
- **ESLint**: Code quality and style enforcement
- **PostCSS**: CSS preprocessing with autoprefixer
- **React Fast Refresh**: Instant component updates during development

## Performance Considerations

- Video assets are preloaded with loading states
- Scroll animations use GSAP ScrollTrigger for optimized performance
- Tailwind CSS ensures minimal CSS output with built-in tree-shaking
- Vite's code splitting automatically optimizes bundle delivery

## Browser Support

Modern browsers with ES2020+ support (Chrome, Firefox, Safari, Edge)

## License

Private project - All rights reserved

---

**Ready to deploy?** Run `npm run build` to generate optimized production files in the `dist/` directory.
