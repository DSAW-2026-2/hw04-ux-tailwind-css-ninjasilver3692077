# AI Log - HW04

## AI Assistance

AI was used during this assignment to support the Figma wireframe process and the migration of the PlayReal landing page from traditional CSS to Tailwind CSS utility classes.

The final decisions, project structure, content, and implementation were reviewed and adjusted to remain consistent with the previous PlayReal assignments.

## Tailwind Color Palette

AI was used to suggest a Tailwind color palette for the landing page.

The suggested palette was based mainly on neutral colors:

- `neutral-100` - main light background
- `neutral-200` - secondary light sections
- `neutral-300` - borders and wireframe-style elements
- `neutral-400` - stronger borders
- `neutral-500` - secondary text
- `neutral-600` - body text
- `neutral-700` - interactive elements
- `neutral-800` - navigation and primary buttons
- `neutral-900` - dark mode sections
- `neutral-950` - dark mode main background

## What I Changed

The original PlayReal design from previous assignments used more visible blue and other colors.

For HW04, I changed the suggested direction to a grayscale palette because the current Figma wireframes are Lo-Fi and use neutral gray tones.

I also used darker neutral values for dark mode while keeping enough contrast between backgrounds, text, borders, and interactive elements.

The final palette was selected to keep the Tailwind landing page visually consistent with the Figma wireframes.

## Tailwind Implementation

The previous CSS-based layout was rebuilt using Tailwind CSS utility classes.

Tailwind utilities are used for:

- Layout
- Spacing
- Typography
- Borders
- Backgrounds
- Responsive design
- Dark mode

Responsive prefixes such as `sm:`, `md:`, and `lg:` are used throughout the page.

## Dark Mode

AI assisted with reviewing the dark mode implementation.

The page uses a visible dark mode toggle.

The selected theme is stored in `localStorage` using the key:

`theme`

The stored value is either:

`dark`

or:

`light`

When the page loads again, the saved preference is restored automatically.

## Figma Assistance

AI was also used to help extend and review the PlayReal Lo-Fi wireframes.

The final Figma project includes the main PlayReal flow:

Group → Challenge → Evidence → Voting → Scoring → Ranking

The wireframes include desktop and mobile layouts as well as active, empty, filled, validation, and error states.