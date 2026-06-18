# Penn State University & Eberly College of Science Style Guide

## Overview
This style guide establishes branding and design standards for Penn State teaching materials, specifically for Penn State Eberly College of Science. For comprehensive brand guidelines, reference [Penn State Brand Book](https://brand.psu.edu/) and the Official Editorial Style Guidance from the Office of Communications.

---

## Typography Standards

### Web Fonts (Primary for Digital)
Per the Penn State Brand Book, **Roboto** is the recommended typeface for web design and has advantages as a web typeface available from Adobe Fonts and Google Fonts.

**Font Stack:**
```css
font-family: 'Roboto', 'Roboto Condensed', -apple-system, BlinkMacSystemFont, 'Segoe UI', sans-serif;
```

Roboto variants available:
- Roboto (Regular, Italic, Medium, Bold, Black)
- Roboto Condensed (Light, Regular, Bold)
- Roboto Slab (for distinctive headings)

### Print Fonts (For Print Materials)
For print materials, use:
- **Proxima Nova** (Proxima Nova, Proxima Nova Condensed)
- **Serifa** (serif alternative)

Note: Proxima Nova renders slightly smaller at the same point size as previous brand fonts.

### Heading Hierarchy (Web)

| Level | Font | Size | Weight | Usage |
|-------|------|------|--------|-------|
| H1 | Roboto | 32px | 500 (Medium) | Page titles, main content headings |
| H2 | Roboto | 24px | 500 (Medium) | Section headers |
| H3 | Roboto | 20px | 500 (Medium) | Subsection headers |
| H4 | Roboto Condensed | 16px | 700 (Bold) | Minor headings, navigation |
| Body | Roboto | 16px | 400 (Regular) | Primary content text |
| Small | Roboto | 14px | 400 (Regular) | Secondary text, captions |

### Line Height & Spacing
- Headings: 1.2
- Body text: 1.6
- Compact text: 1.4

---

## Penn State Official Colors

### Primary Colors
- **Navy Blue**: `#001E44` (Penn State Official Blue)
  - Primary brand color
  - Used for headers, buttons, and primary navigation
  
- **White**: `#FFFFFF`
  - Background and text contrast
  
- **Limestone**: `#E7E4DC` (Penn State Limestone)
  - Accent backgrounds and borders

### Secondary Colors
- **Nittany Navy**: `#1E3A5E`
  - Darker alternative for hover states
  
- **Lionsgate Gold**: `#E98300` (Penn State Orange)
  - Accent color for calls-to-action and highlights
  
- **Forestry Green**: `#7FB04A` (Science specific)
  - Science discipline accent

### Supporting Colors
- **Alert Red**: `#D93D00`
  - Errors and warnings
  
- **Success Green**: `#4DA82F`
  - Success messages
  
- **Informational Blue**: `#006BA6`
  - Information callouts

---

## Typography

### Font Stack
```css
font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', 'Helvetica Neue', sans-serif;
```

### Heading Hierarchy

| Level | Size | Weight | Usage |
|-------|------|--------|-------|
| H1 | 32px | 700 Bold | Page titles, main content headings |
| H2 | 24px | 700 Bold | Section headers |
| H3 | 20px | 600 Semibold | Subsection headers |
| H4 | 16px | 600 Semibold | Minor headings |
| Body | 16px | 400 Regular | Primary content text |
| Small | 14px | 400 Regular | Secondary text, captions |

### Line Height
- Headings: 1.2
- Body text: 1.6
- Compact text: 1.4

---

## Eberly College of Science Branding

### Institutional Context
The Eberly College of Science is Penn State's premier science education and research college, encompassing:
- Department of Astrobiology
- Department of Biology
- Department of Chemistry
- Department of Mathematics
- Department of Physics
- Department of Statistics

### Science Discipline Accent
Use **Forestry Green** (`#7FB04A`) to denote science-specific content, lab materials, and scientific processes.

---

## Component Styling

### Buttons

#### Primary Button
```css
background-color: #001E44; /* Penn State Navy */
color: #FFFFFF;
padding: 12px 24px;
border: none;
border-radius: 4px;
font-family: 'Roboto', sans-serif;
font-weight: 500;
font-size: 16px;
cursor: pointer;
transition: background-color 0.2s ease;
```

```css
/* Hover State */
background-color: #1E3A5E; /* Nittany Navy */
```

#### Secondary Button
```css
background-color: transparent;
color: #001E44;
border: 2px solid #001E44;
padding: 10px 22px;
border-radius: 4px;
font-family: 'Roboto', sans-serif;
font-weight: 500;
font-size: 16px;
cursor: pointer;
transition: all 0.2s ease;
```

```css
/* Hover State */
background-color: #001E44;
color: #FFFFFF;
```

#### Accent Button
```css
background-color: #E98300; /* Lionsgate Gold */
color: #FFFFFF;
padding: 12px 24px;
border: none;
border-radius: 4px;
font-family: 'Roboto', sans-serif;
font-weight: 500;
font-size: 16px;
cursor: pointer;
transition: background-color 0.2s ease;
```

```css
/* Hover State */
background-color: #d97600;
```

### Navigation Bar
- Background: `#001E44` (Penn State Navy)
- Text: `#FFFFFF`
- Active state: `#E98300` (Lionsgate Gold)
- Hover state: `#1E3A5E` (Nittany Navy)

### Cards & Containers
- Background: `#FFFFFF`
- Border: 1px solid `#E7E4DC` (Limestone)
- Shadow: `0 2px 8px rgba(0, 30, 68, 0.1)`
- Padding: 20px

### Callout Boxes

#### Important/Science
```css
background-color: rgba(127, 176, 74, 0.1); /* Forestry Green */
border-left: 4px solid #7FB04A;
padding: 12px 16px;
```

#### Alert/Warning
```css
background-color: rgba(217, 61, 0, 0.1); /* Alert Red */
border-left: 4px solid #D93D00;
padding: 12px 16px;
```

#### Success
```css
background-color: rgba(77, 168, 47, 0.1); /* Success Green */
border-left: 4px solid #4DA82F;
padding: 12px 16px;
```

---

## Spacing & Layout

### Standard Spacing Scale
```
4px   - Minimum spacing
8px   - Tight spacing
12px  - Small spacing
16px  - Base spacing
20px  - Medium spacing
24px  - Large spacing
32px  - Extra large spacing
```

### Container
- Max-width: 1200px
- Padding: 20px on sides (responsive: 12px on mobile)
- Center alignment with `margin: 0 auto`

### Section Spacing
- Between sections: 48px
- Between elements: 16px
- Between paragraphs: 12px

---

## Accessibility Standards

### Color Contrast
All text must meet WCAG AA standards:
- Normal text: Minimum 4.5:1 contrast ratio
- Large text (18pt+): Minimum 3:1 contrast ratio

### Text Readability
- Minimum font size: 14px for body text
- Maximum line length: 75-85 characters for optimal reading
- Use semantic HTML (`<h1>`, `<h2>`, `<button>`, etc.)

### Focus States
- All interactive elements must have visible focus indicators
- Focus outline: `2px solid #E98300` (Lionsgate Gold)
- Focus outline offset: `2px`

---

## Logo & Branding Assets

### Penn State Logo
- Use official Penn State logo with proper clearance
- Minimum size: 40px width
- Always include ™ symbol
- Download from: [Penn State Visual Identity Standards](https://brand.psu.edu/)

### Eberly College Identifier
When including college-specific branding:
```
Eberly College of Science
The Pennsylvania State University
```

---

## Editorial Style Guidelines

Per the Eberly College of Science Editorial Style Guidance:

### Institutional Names
- **Penn State** (not PSU, Penn State University, or The Pennsylvania State University)
- **Penn State Eberly College of Science** (not ECoS or College of Science; use "the college" on subsequent mention)
- **Penn State University Park** (initial mention); University Park campus (subsequent mentions)

### Titles & Degrees
- Capitalize titles when they precede names: *Dean Tracy Langkilde*, *Professor Doug Cavener*
- Lowercase after names: *Tracy Langkilde, professor of biology*
- Always capitalize named professorships/chairs: *Evan Pugh University Professor of Chemistry*
- Spell out academic degrees: *bachelor of science degree in physics*, *master's degree in chemistry*
- Abbreviate with periods, no spaces: *B.A., M.S., Ph.D., M.B.A., M.D.*
- Plurals: *B.A.'s, M.A.'s, Ph.D.'s*

### Academic Programs
- Capitalize program names when specific: *Astronomy and Astrophysics major*
- Lowercase generic terms: *the major, the minor, the program*
- Capitalize department names: *Department of Chemistry*, lowercase informal: *the chemistry department*

### Dates & Times
- Spell out months: *October 6* (not Oct. 6th)
- Include zeroes, space, periods: *8:00 a.m.–5:00 p.m.*
- Exceptions: *noon* and *midnight* (not 12:00 a.m./p.m.)
- Time zones in parentheses: *(EDT)*

### Emphasis
- Use italics sparingly for occasional emphasis
- Avoid overusing; limit boldface and underlining to formal contexts
- Never capitalize entire words for emphasis in formal prose
- Reference Chicago Manual of Style 7.50–7.52 for guidance

---

## Code Examples

### Basic HTML Structure
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Penn State Eberly College of Science - Teaching Guide</title>
  <link rel="stylesheet" href="styles/main.css">
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;500;700&family=Roboto+Condensed:wght@700&display=swap" rel="stylesheet">
</head>
<body>
  <nav class="navbar"><!-- Navigation here --></nav>
  <main class="container"><!-- Main content --></main>
  <footer class="footer"><!-- Footer --></footer>
</body>
</html>
```

### CSS Variables (Recommended)
```css
:root {
  --penn-navy: #001E44;
  --nittany-navy: #1E3A5E;
  --lionsgate-gold: #E98300;
  --forestry-green: #7FB04A;
  --limestone: #E7E4DC;
  --alert-red: #D93D00;
  --success-green: #4DA82F;
  --info-blue: #006BA6;
  
  --spacing-xs: 4px;
  --spacing-sm: 8px;
  --spacing-md: 16px;
  --spacing-lg: 24px;
  --spacing-xl: 32px;
}
```

---

## Resources

- [Penn State Brand Book](https://brand.psu.edu/) - Official branding guidelines
- [Penn State Design Essentials](https://brand.psu.edu/design-toolkit/design-essentials) - Design standards
- [Penn State Brand Book: Fonts](https://brand.psu.edu/) - Official font specifications
- [Eberly College of Science](https://science.psu.edu/) - College website
- [Editorial Style Guidance](https://science.psu.edu/) - Eberly College editorial standards
- [WCAG 2.1 Accessibility Guidelines](https://www.w3.org/WAI/WCAG21/quickref/) - Web accessibility
- [Chicago Manual of Style](https://www.chicagomanualofstyle.org/) - Reference for editorial standards

---

## Questions?
For branding questions or inconsistencies, refer to Penn State's official brand guidelines or contact the Eberly College of Science communications office.
