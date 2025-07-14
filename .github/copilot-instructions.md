<!-- Use this file to provide workspace-specific custom instructions to Copilot. For more details, visit https://code.visualstudio.com/docs/copilot/copilot-customization#_use-a-githubcopilotinstructionsmd-file -->

# Copilot Instructions for CSS Box Model Project

## Project Overview
This is an educational project demonstrating the CSS Box Model implementation using SASS 7-1 pattern. The project focuses on proper implementation of margin, border, padding, and content properties according to specific design requirements.

## Project Structure and Patterns

### SASS 7-1 Pattern
Follow the established 7-1 architecture:
- `abstracts/`: Variables and mixins for box model specifications
- `base/`: Reset and base styles
- `components/`: Reusable UI components (buttons, cards)
- `layout/`: Layout-specific styles (header, main, footer)

### Box Model Requirements
When working with this project, always consider:
- Container: 80% width, centered, 1px gray border, 20px padding
- Header: 100% viewport width, 10px padding, solid background
- Footer: 100px height, 20px padding, 50px top margin
- Buttons: Internal padding, defined borders, margin spacing, rounded corners, hover effects

### Naming Conventions
- Use BEM (Block Element Modifier) methodology for CSS classes
- SASS variables should follow the pattern: `$component-property-modifier`
- Mixins should be descriptive: `@mixin button-base`, `@mixin respond-to`

## Code Style Guidelines

### SASS/CSS
- Always use box-sizing: border-box
- Implement mobile-first responsive design
- Use semantic mixins for repetitive box model patterns
- Maintain consistent spacing using predefined variables
- Include proper transitions and hover states for interactive elements

### HTML
- Use semantic HTML5 elements
- Include proper ARIA attributes for accessibility
- Maintain consistent class naming with BEM methodology
- Ensure responsive image handling

### JavaScript
- Focus on progressive enhancement
- Implement smooth scrolling and interactive features
- Add proper event listeners for button interactions
- Include accessibility considerations (keyboard navigation, screen readers)

## Responsive Design
- Mobile-first approach with min-width media queries
- Adjust container width at different breakpoints
- Reduce padding/margins on smaller screens
- Ensure touch-friendly button sizes on mobile

## Performance Considerations
- Optimize SASS compilation for production
- Use efficient selectors
- Minimize reflows and repaints
- Implement proper lazy loading if needed

## Accessibility
- Maintain proper color contrast ratios
- Include focus states for keyboard navigation
- Use semantic markup and ARIA labels
- Ensure all interactive elements are accessible

When generating code for this project, prioritize:
1. Proper CSS Box Model implementation
2. SASS 7-1 pattern compliance
3. Responsive design principles
4. Clean, maintainable code structure
5. Accessibility best practices
