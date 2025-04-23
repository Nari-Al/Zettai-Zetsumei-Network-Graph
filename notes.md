

✅ Google Sheets — UX Improvements
These make it easier for contributors to add data, avoid mistakes, and feel welcomed.

1. Add a README tab
A clean “Instructions” tab at the start helps onboard new users:

How to add a character

How to define relationships

Color legend

Valid group names (optional: use data validation)

2. Data validation dropdowns
For columns like:

Relation Type: Dropdown with only “Amour”, “Rivalité”, “Amitié”, etc.

Group: Limit to known groups to avoid typos (e.g., “Cathédrale” vs “Cathedrale”) This avoids silent rendering errors.

3. Auto-formatting / conditional colors
Highlight errors in red (e.g., missing ID or name)

Use light coloring to group rows by character or group

You can even lightly color code by group to match graph colors

4. Hyperlinks for character references
If characters have bios elsewhere (RP forums, toyhou.se, etc), add a column like Link and embed hyperlinks. You could show them in tooltips or info boxes later.

✅ Graph Page — Easy Visual/UX Tweaks
Minimal work, big reward.

1. Better spacing and visual hierarchy
Use padding/margin to visually separate:

Graph container

Filters / controls

Info card / legend

Tailwind, Grid, or Flexbox can handle this fast.

2. Persistent UI
If you have filters or toggles, don’t make users reselect them on refresh. Save UI state in localStorage.

3. Clickable nodes should feel clicky
Add a hover effect (e.g., glow or cursor pointer) so it’s obvious nodes are interactive.

4. Highlight on hover
When hovering a node, slightly dim other nodes and highlight:

The node itself

Direct links

Connected nodes

Adds immediate visual context.

5. Loading screen
If parsing Google Sheets takes a second, show a quick loading spinner and message like “Fetching divine destinies...”

6. Responsive layout
Make the legend collapsible on small screens. You can also auto-scale the graph to fit the screen initially.

If you want, I can mock up a cleaner sheet format or help you tweak the graph layout CSS. Want a quick redesign of your spreadsheet’s structure or a minimal upgraded HTML layout for the page?