---
name: KESHASHA ERP System
colors:
  surface: '#f8f9ff'
  surface-dim: '#ccdbf2'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eef4ff'
  surface-container: '#e5efff'
  surface-container-high: '#dbe9ff'
  surface-container-highest: '#d4e4fa'
  on-surface: '#0d1c2d'
  on-surface-variant: '#434652'
  inverse-surface: '#233143'
  inverse-on-surface: '#e9f1ff'
  outline: '#747783'
  outline-variant: '#c4c6d3'
  surface-tint: '#345baf'
  primary: '#002869'
  on-primary: '#ffffff'
  primary-container: '#0b3d91'
  on-primary-container: '#8dadff'
  inverse-primary: '#b1c5ff'
  secondary: '#436086'
  on-secondary: '#ffffff'
  secondary-container: '#b3d1fd'
  on-secondary-container: '#3c597f'
  tertiary: '#252d35'
  on-tertiary: '#ffffff'
  tertiary-container: '#3b434c'
  on-tertiary-container: '#a7b0ba'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2ff'
  primary-fixed-dim: '#b1c5ff'
  on-primary-fixed: '#001947'
  on-primary-fixed-variant: '#144296'
  secondary-fixed: '#d3e3ff'
  secondary-fixed-dim: '#abc8f4'
  on-secondary-fixed: '#001c39'
  on-secondary-fixed-variant: '#2a486d'
  tertiary-fixed: '#dbe3ee'
  tertiary-fixed-dim: '#bfc7d2'
  on-tertiary-fixed: '#141c24'
  on-tertiary-fixed-variant: '#404851'
  background: '#f8f9ff'
  on-background: '#0d1c2d'
  surface-variant: '#d4e4fa'
typography:
  headline-lg:
    fontFamily: IBM Plex Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 26px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: IBM Plex Sans
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 22px
    letterSpacing: 0em
  headline-sm:
    fontFamily: IBM Plex Sans
    fontSize: 13px
    fontWeight: '600'
    lineHeight: 18px
    letterSpacing: 0.01em
  body-lg:
    fontFamily: IBM Plex Sans
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 18px
  body-md:
    fontFamily: IBM Plex Sans
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  body-sm:
    fontFamily: IBM Plex Sans
    fontSize: 11px
    fontWeight: '400'
    lineHeight: 14px
  data-mono:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
  data-mono-sm:
    fontFamily: JetBrains Mono
    fontSize: 11px
    fontWeight: '400'
    lineHeight: 14px
  label-caps:
    fontFamily: IBM Plex Sans
    fontSize: 10px
    fontWeight: '700'
    lineHeight: 12px
    letterSpacing: 0.05em
  window-title:
    fontFamily: IBM Plex Sans
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
spacing:
  gutter: 0.5rem
  gutter-dense: 0.25rem
  margin: 0.75rem
  space-xs: 0.125rem
  space-sm: 0.25rem
  space-md: 0.5rem
  space-lg: 0.75rem
  space-xl: 1rem
---

## Brand & Style

This design system channels the rigorous, data-dense utility of classic tier-1 enterprise enterprise resource planning (ERP) suites, modernized with precision rendering and ergonomic clarity. Built for mission-critical accounting, supply chain logistics, multi-entity consolidation, and warehouse workflows, the visual language prioritizes maximum field density, deterministic keyboard navigation, and immediate data scannability over decorative flair.

The core aesthetic synthesizes **Corporate / Modern** enterprise discipline with **Functional Utilitarianism**:
- **Information Density over Airiness:** Interfaces avoid gratuitous whitespace in operational screens, relying on strict structural alignment and razor-sharp separation lines.
- **Multiple Document Interface (MDI):** Emulates classic desktop power-user ergonomics inside the web canvas—featuring floating, resizable window layers with authoritative titlebars, status bars, and persistent docking states.
- **Clarity & Auditability:** Visual cues mirror tangible enterprise hardware and classic SAP workflows—active editing cells exhibit unmistakable yellow active-state tints, status indicators use unequivocal semantic codes, and all data grids expose visible, high-definition cell boundaries.

## Colors

The palette is engineered around high functional contrast, clear state indication, and reduced eye strain during 8-hour continuous data entry:

- **Primary Core (`#0b3d91` to `#072a66`):** The authoritative enterprise navy. Applied to active MDI window headers, primary transaction commit bars, active master menu ribbons, and high-priority action buttons.
- **Secondary Structural (`#3d5a80`):** Muted slate navy used for inactive/unfocused window frames, table column sort headers, tab strip backgrounds, and secondary command palettes.
- **Surfaces & Canvas (`#f4f6f9`, `#eef1f6`, `#ffffff`):** Layered neutral grays. `#f4f6f9` establishes the main canvas/workspace desk background, `#eef1f6` forms panel headers and read-only field fills, and pure `#ffffff` is strictly reserved for live, editable document canvases and active data grid rows.
- **Grid Dividers & Rules (`#c5cdd8`, `#94a3b8`):** Structural borders for table cells, docked panes, and fieldset partitions. Never rely on borderless edge-blurs; every grid cell possesses an explicit physical perimeter.
- **Operational Data Highlights:**
  - **Editable Field Active Focus:** `#fffef0` (classic SAP soft ledger yellow) paired with an inner border of `#0b3d91` ensures instantaneous cursor recognition across hundreds of inputs.
  - **Read-Only / Display-Only Cell:** `#eef1f6` with `#475569` text.
  - **Transaction States:**
    - Success/Posted: `#1e7e34` (forest green) on `#e8f5e9`
    - In Review/Draft: `#b45309` (deep amber) on `#fef3c7`
    - Voided/Discrepancy: `#b91c1c` (crimson) on `#fee2e2`
    - Open/Active: `#0b3d91` on `#e0eafc`

## Typography

Typography in this system adheres to strict mechanical legibility and high spatial efficiency:

- **Primary Typeface (`IBM Plex Sans`):** Selected for its industrial heritage, engineered vertical metrics, and distinct glyph differentiation (distinguishing capital `I`, lowercase `l`, and digit `1` unambiguously).
- **Tabular & Code Typeface (`JetBrains Mono`):** Standard for numeric amounts, ledger codes, currency balances, SKU/barcode strings, tax IDs, and document tracking numbers. Enforces uniform vertical column alignment without character jitter.
- **Hierarchy Rules:**
  - Base body and inputs standardize at `12px` (`body-md`), providing maximum field density without losing legibility.
  - Form field labels use `11px` bold or uppercase styling (`label-caps`) to establish direct vertical proximity to entry boxes.
  - Window titlebars utilize `12px` semibold (`window-title`) with slight tracking for fast multi-window triage in taskbars.

## Layout & Spacing

The layout model implements a structured, dense enterprise desktop viewport featuring docked sidebars, a modular workspace, and a Multiple Document Interface (MDI) canvas:

- **Desktop Shell Rhythm:**
  - **Top Application Header:** Fixed height of 36px (global search, entity switcher, utility badges).
  - **Command/Toolbar Ribbon:** Fixed height of 28px (classic New, Find, First, Previous, Next, Last, Print, Export icons).
  - **MDI Work Area:** Fluid grid container allowing internal floating dialogs or tiled document panels with sticky headers and scrollable row areas.
  - **MDI Bottom Taskbar / Status Bar:** Fixed height of 26px anchoring minimized window chips, operational locks, user session status, and total row counters.
- **Grid & Form Alignment:**
  - Primary form areas adopt a compact 12-column layout with fixed field labeling: label left (30% width), input right (70% width), or stacked with 2px vertical gap (`space-xs`).
  - Table gutters use `gutter-dense` (4px / `0.25rem`) padding per cell horizontally and 3px vertically, maximizing rows displayed per viewport without requiring pagination.
- **Reflow and Breakpoints:**
  - Optimized for desktop screens (`>= 1280px`).
  - Between `1024px` and `1279px`, multi-window floating mode transitions to a single-tabbed active layout.
  - Below `1024px`, MDI windows force auto-maximize into full-screen tabbed panels with horizontal table scrolling.

## Elevation & Depth

Rather than relying on modern blurred shadows or dramatic light simulation, depth is established through **structural border layering and crisp bevel contrasts**:

- **Floating MDI Windows (Active):**
  - Outlined with a solid 1px border of `#072a66`.
  - Layered with an engineered drop shadow: `0 4px 12px rgba(7, 42, 102, 0.22), 0 1px 3px rgba(0, 0, 0, 0.15)`.
  - Window Header: Solid `#0b3d91` background with white text and functional window controls (minimize, maximize, close).
- **Floating MDI Windows (Inactive / Unfocused):**
  - Outlined with 1px border of `#94a3b8`.
  - Shallow shadow: `0 2px 6px rgba(0, 0, 0, 0.10)`.
  - Window Header: Solid `#3d5a80` background with light-slate text.
- **In-Canvas Panels & Group Boxes:**
  - Enclosed in a 1px border (`#c5cdd8`) with a flat `#ffffff` or `#f4f6f9` surface. Zero shadow. Group box legends break the top border line in classic desktop tradition.
- **Dropdowns, Context Menus, and Autocomplete Lists:**
  - Border: 1px solid `#94a3b8`.
  - Shadow: Crisp, non-diffuse `0 4px 8px rgba(0, 0, 0, 0.16)`.

## Shapes

The shape system is strictly **Sharp (`roundedness: 0`)**:

- **Zero Border Radius (`0px`):** Applied uniformly to inputs, table cells, MDI window containers, window control buttons, context menus, tabs, and command ribbons.
- **Intentionality:** Sharp corners reinforce the mechanical, authoritative feel of an industrial financial tool, preserve pixel sharpness across high-DPI displays, and maximize printable/viewable data surface down to the single pixel.
- **Exceptions:** Status badges/pills are permitted a micro-radius of 2px where needed to distinguish metadata tags from editable input containers.

## Components

### 1. MDI Windows & Titlebars
- **Header Structure:** 26px height. Active window uses `#0b3d91` fill, crisp white 12px bold title, and right-aligned button cluster (Minimize `_`, Maximize/Restore `□`, Close `×`).
- **Window Controls:** 22px × 20px clickable zones. Hover on close button changes fill to `#c53030` (classic alert red).
- **Body & Resizers:** 1px border `#0b3d91` framing the document body. Resizer grips on bottom-right corner use a diagonal micro-stipple pattern.

### 2. Data Tables (Grids)
- **Header:** Sticky top, 24px height, background `#eef1f6`, border bottom 2px solid `#94a3b8`, vertical dividers 1px solid `#c5cdd8`. Header text is `label-caps` in `#334155`.
- **Rows:** 22px fixed height. Alternating striping: `#ffffff` for even rows, `#f8fafc` for odd rows.
- **Cell Dividers:** 1px solid `#c5cdd8` on all four edges.
- **Selection:** Active row receives background `#dbeafe` with a 1px dotted outline or `#0b3d91` left indicator bar. Selected individual cell has 1px outline `#0b3d91`.
- **Numeric Columns:** Right-aligned with `JetBrains Mono` typography.

### 3. Form Input Fields
- **Standard State:** 22px height, 1px border `#94a3b8`, background `#ffffff`, text `body-md` in `#0f172a`.
- **Active Focus State:** Background instantly shifts to classic SAP yellow (`#fffef0`) with a 1px solid `#0b3d91` border.
- **Read-Only / System Generated:** Background `#eef1f6`, text `#64748b`, border `#c5cdd8`.
- **Search / Linked Record Picker (Choose from List):** Standard input paired with an integrated 18px square trigger button on the right containing an ellipses `...` or magnifying glyph.

### 4. Command Ribbon & Action Buttons
- **Primary Transaction Commit (Add / Update / OK):** Height 24px, background `#0b3d91`, text `#ffffff`, border 1px solid `#072a66`, hover `#072a66`.
- **Secondary / Cancel Button:** Height 24px, background `#f1f5f9`, text `#1e293b`, border 1px solid `#94a3b8`, hover `#e2e8f0`.
- **Toolbar Icon Buttons:** 24px × 24px square, flat surface, 1px transparent border, hovering adds 1px solid `#94a3b8` with `#eef1f6` background.

### 5. Checkboxes & Radio Buttons
- 13px × 13px square boxes. 1px solid `#94a3b8` with `#ffffff` interior. Checked state displays `#0b3d91` tick mark or center square. Zero border radius.

### 6. Document Status Badges
- Displayed in window headers and summary panels: 18px height, 1px border, uppercase 10px bold text.
  - Open: `#0b3d91` text, `#e0eafc` background, `#0b3d91` border.
  - Closed / Cleared: `#1e7e34` text, `#e8f5e9` background, `#1e7e34` border.
  - Cancelled: `#b91c1c` text, `#fee2e2` background, `#b91c1c` border.

### 7. Bottom ERP Taskbar
- Fixed at viewport base. Houses the start/menu toggle, active window tabs (22px height buttons displaying window name with blue stripe on the active item), system timestamp, database tenant name (`KESHASHA_LIVE_PROD`), and current active exchange rates.