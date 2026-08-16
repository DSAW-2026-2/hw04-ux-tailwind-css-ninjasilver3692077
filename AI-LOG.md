# AI Log - HW04

## AI Assistance

AI was used during this assignment to support the Figma wireframe process and the migration of the PlayReal landing page from traditional CSS to Tailwind CSS utility classes.

The final decisions, project structure, content, and implementation were reviewed and adjusted to remain consistent with the previous PlayReal assignments.

## Tailwind Color Palette

AI first suggested a neutral palette because the Figma work is deliberately Lo-Fi. The final landing palette keeps neutral `slate` colors for readable body text and dark mode, but restores PlayReal's recognizable colors:

- `blue-50` - light page sections and soft surfaces
- `blue-100` and `blue-200` - borders and supporting surfaces
- `blue-600` and `blue-700` - navigation, primary buttons, links, and visual emphasis
- `blue-800` and `blue-950` - darker borders and the main display heading
- `emerald-50` and `emerald-700` - active challenge and positive progress states
- `amber-50` and `amber-700` - ranking-related status
- `slate-600` - readable body text
- `slate-800`, `slate-900`, and `slate-950` - dark mode surfaces

## What I Changed

The Figma wireframes remain grayscale because they are intentionally Lo-Fi, as requested for the wireframe deliverable. The landing page has a different role: it communicates the visual identity of the PlayReal product.

For that reason, I restored blue as the main brand color for navigation, actions, borders, and visual emphasis. I added green and amber only where they communicate meaningful states, such as an active challenge, streak, or ranking. The dark mode keeps slate surfaces so the blue actions remain clear and readable.

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

## What I Learned About Tailwind

Reviewing and adjusting the generated classes showed me that Tailwind utilities are small decisions that combine to form a layout. I learned that a class without a prefix applies first on mobile, while `sm:`, `md:`, and `lg:` progressively adjust the layout for larger screens.

I also learned that `dark:` is a variant that can be combined with normal utilities, such as `dark:bg-slate-900` and `dark:text-slate-100`. It does not create a dark theme by itself; the page still needs to add or remove the `dark` class and save that preference in `localStorage`.

Most importantly, reviewing the code helped me see that brand color should be used intentionally. Blue is reserved for PlayReal actions and emphasis, while green and amber represent meaningful progress states instead of decorative color.

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
