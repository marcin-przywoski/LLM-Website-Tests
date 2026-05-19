# Design System: DevOps Resume

## Color Palette

### Primary Palette (OKLCH)
- **Accent**: `oklch(55% 0.15 264)` – Electric blue (primary action, highlights)
- **Accent Dark**: `oklch(45% 0.12 264)` – Deeper blue (hover states)
- **Success**: `oklch(65% 0.14 142)` – Emerald green (achievements, metrics up)
- **Warning**: `oklch(65% 0.14 52)` – Warm amber (important callouts)

### Neutral Palette
- **Background Dark**: `oklch(12% 0.01 240)` – Near-black with blue tint
- **Surface**: `oklch(18% 0.01 240)` – Card/container surface
- **Border**: `oklch(25% 0.01 240)` – Subtle dividers
- **Text Primary**: `oklch(95% 0.01 240)` – Near-white, warm tinted
- **Text Secondary**: `oklch(75% 0.01 240)` – Dimmed text
- **Text Tertiary**: `oklch(55% 0.01 240)` – Very dimmed (dates, labels)

## Typography

### Font Stack
- **Headings**: `-apple-system, BlinkMacSystemFont, "Segoe UI", "Helvetica Neue", sans-serif`
- **Body**: Same system font stack (unified, modern)
- **Mono (code/tech)**: `"Monaco", "Menlo", "Ubuntu Mono", monospace`

### Scale (ratios)
- **H1**: 2.5rem (40px)
- **H2**: 2rem (32px)
- **H3**: 1.5rem (24px)
- **H4**: 1.25rem (20px)
- **Body**: 1rem (16px)
- **Small**: 0.875rem (14px)
- **Tiny**: 0.75rem (12px)

### Weight Hierarchy
- **Regular**: 400 (body, descriptions)
- **Medium**: 500 (labels, secondary headings)
- **Semibold**: 600 (section headers)
- **Bold**: 700 (emphasis, key metrics)

## Spacing
- **XS**: 0.25rem (4px) – Micro spacing
- **S**: 0.5rem (8px) – Compact groups
- **M**: 1rem (16px) – Standard spacing
- **L**: 1.5rem (24px) – Section breathing room
- **XL**: 2.5rem (40px) – Major section breaks
- **2XL**: 4rem (64px) – Top-level sections

## Components

### Stat Boxes
- Background: `oklch(18% 0.01 240)` with `1px` border `oklch(25% 0.01 240)`
- Accent top border: `3px` in accent color
- Rounded corners: `8px`
- Padding: `1.5rem` (24px)
- Number: Bold, accent color, large scale
- Label: Small, secondary text

### Skill Pills
- Background: `oklch(25% 0.01 240)`
- Text: Primary text color
- Border radius: `20px`
- Padding: `0.5rem 1rem` (8px 16px)
- Hover: Background shifts to `oklch(32% 0.01 240)`, slight scale 1.05

### Timeline Items
- Left border accent: `3px` in accent color (vertical)
- Connector dots between items (pseudo-element circles)
- Year label: Tertiary text, bold, positioned
- Description: Secondary text

### Metric Cards
- Combine stat boxes with icon areas
- Icon: Accent color, large (32–48px)
- Metric number: Largest weight (bold)
- Context: Small secondary text

## Layout

### Grid/Sections
- **Container max-width**: 1000px
- **Section padding**: `4rem 2rem` (64px 32px on desktop, 2rem 1rem mobile)
- **Columns**: 1-column single-column baseline; 2-column for side-by-side stats or skills

### Card Spacing
- **Gap between cards**: 1.5rem (24px)
- **Internal card padding**: 1.5–2rem (24–32px)
- **No nested cards** (single-level hierarchy)

## Motion & Interaction

### Transitions
- **Default easing**: `cubic-bezier(0.23, 1, 0.320, 1)` (ease-out-quart)
- **Duration**: 200ms for micro (hover), 400ms for macro (scroll reveals)

### Micro-interactions
- **Hover on links/buttons**: Color shift + subtle scale (1.02)
- **Scroll reveals**: Cards/sections fade in + slight translateY (20px → 0)
- **Stat number animations**: Count-up on viewport entry (smooth number transitions)

## Accessibility
- **Contrast**: All text ≥ 4.5:1 WCAG AA
- **Focus states**: Visible outline on interactive elements
- **Color not alone**: Icons + text for semantic meaning
- **Readable line length**: 50–70 characters

## Responsive Breakpoints
- **Mobile**: < 640px (single column, larger padding/spacing)
- **Tablet**: 640px–1024px (flexible grid)
- **Desktop**: > 1024px (full layout with 1000px container)

## Code/Tech Stack Display
- **Monospace font** for technology names
- **Accent color highlighting** for key technologies
- **Inline badges** vs. list format depending on context
- No syntax highlighting needed (simplified for resume)

## Animations Timeline
- **Page load**: Staggered fade-in for sections (100ms delay between)
- **Section entry**: Subtle slide-up + fade (on scroll)
- **Stat numbers**: Count-up animation when visible (1s duration)
- **Hover states**: Color + micro-scale transitions (200ms)
