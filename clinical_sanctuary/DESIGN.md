---
name: Clinical Sanctuary
colors:
  surface: '#f1fcf7'
  surface-dim: '#d1ddd8'
  surface-bright: '#f1fcf7'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#ebf6f1'
  surface-container: '#e5f0eb'
  surface-container-high: '#dfebe6'
  surface-container-highest: '#dae5e0'
  on-surface: '#141e1b'
  on-surface-variant: '#41493e'
  inverse-surface: '#28332f'
  inverse-on-surface: '#e8f3ee'
  outline: '#717a6d'
  outline-variant: '#c0c9bb'
  surface-tint: '#2a6b2c'
  primary: '#00450d'
  on-primary: '#ffffff'
  primary-container: '#1b5e20'
  on-primary-container: '#90d689'
  inverse-primary: '#91d78a'
  secondary: '#1b6d24'
  on-secondary: '#ffffff'
  secondary-container: '#a0f399'
  on-secondary-container: '#217128'
  tertiary: '#323e36'
  on-tertiary: '#ffffff'
  tertiary-container: '#49554c'
  on-tertiary-container: '#bcc9be'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#acf4a4'
  primary-fixed-dim: '#91d78a'
  on-primary-fixed: '#002203'
  on-primary-fixed-variant: '#0c5216'
  secondary-fixed: '#a3f69c'
  secondary-fixed-dim: '#88d982'
  on-secondary-fixed: '#002204'
  on-secondary-fixed-variant: '#005312'
  tertiary-fixed: '#d9e6da'
  tertiary-fixed-dim: '#bdcabe'
  on-tertiary-fixed: '#131e17'
  on-tertiary-fixed-variant: '#3e4a41'
  background: '#f1fcf7'
  on-background: '#141e1b'
  surface-variant: '#dae5e0'
  surface-pure: '#FFFFFF'
  surface-soft: '#F8FAF9'
  surface-muted: '#F1F5F2'
  border-subtle: '#E2E8E5'
  border-input: '#D1DBD5'
  text-secondary: '#4A5568'
  text-muted: '#7D8A85'
  priority-emergency-bg: '#FFEBEE'
  priority-emergency-text: '#C62828'
  priority-urgency-bg: '#FFF8E1'
  priority-urgency-text: '#F57F17'
  priority-standard-bg: '#E8F5E9'
  priority-standard-text: '#2E7D32'
typography:
  display-ticket:
    fontFamily: lexend
    fontSize: 96px
    fontWeight: '700'
    lineHeight: 104px
    letterSpacing: -0.02em
  display-ticket-mobile:
    fontFamily: lexend
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.01em
  display-room:
    fontFamily: lexend
    fontSize: 56px
    fontWeight: '600'
    lineHeight: 64px
    letterSpacing: -0.01em
  display-room-mobile:
    fontFamily: lexend
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: '0'
  headline-lg:
    fontFamily: lexend
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: lexend
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-sm:
    fontFamily: lexend
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: manrope
    fontSize: 18px
    fontWeight: '500'
    lineHeight: 28px
  body-md:
    fontFamily: manrope
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: manrope
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: manrope
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
    letterSpacing: 0.01em
  label-md:
    fontFamily: manrope
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-sm:
    fontFamily: manrope
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.04em
  caption:
    fontFamily: manrope
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.03em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  space-2xs: 0.25rem
  space-xs: 0.5rem
  space-sm: 0.75rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2rem
  space-2xl: 3rem
  space-3xl: 4rem
  gutter-mobile: 1rem
  gutter-desktop: 1.5rem
  margin-mobile: 1rem
  margin-desktop: 2rem
---

## Brand & Style

This design system is tailored for critical healthcare environments, triage desks, and public queue calling displays (totems and waiting room displays). The core ethos balances clinical authority with human-centered empathy: it must feel calming to anxious patients while presenting crystal-clear, unambiguous data to medical professionals under high cognitive load.

The design movement applied is **Modern Clinical Functionalism**—a synthesis of high-contrast minimalism and tactile, clean physical metaphors. It rejects visual clutter, decorative noise, and over-saturated novelty in favor of clinical serenity:
- **Crisp, hygienic purity**: Pure whites and subtle sage-tinted neutrals evoke a sanitized, controlled, and serene atmosphere.
- **Authoritative clarity**: Deep clinical greens denote stability, recovery, and precision, steering clear of stark institutional coldness.
- **Cognitive priority**: Status indicators and call displays leverage universal triage color standards (Manchester triage protocol cues) with WCAG AAA-level contrast to guarantee instant legibility at 10 meters distance.

## Colors

The palette is engineered around accessibility, rapid triage recognition, and clinical calm.

- **Primary (`#1B5E20`) & Secondary (`#2E7D32`)**: Rich, botanical forest greens provide high-contrast grounding for primary operational buttons ("Call Next Ticket", "Confirm Admission") and prominent navigational items.
- **Tertiary (`#E8F5E9`)**: A delicate mint-tinted wash used for active list selections, focus envelopes, and informational backgrounds.
- **Neutral (`#1A2421`)**: A deep spruce-tinted black that eliminates eye strain caused by pure `#000000` while delivering superior readability.
- **Surfaces**: Layered with `#F8FAF9` as the global canvas background to preserve optical hygiene without the glare of harsh white screens, while `#FFFFFF` elevates active interactive cards, modal dialogs, and calling panels.
- **Triage Badges**: Hardened status tokens (Emergency Red `#C62828`, Urgency Amber `#F57F17`, Standard Green `#2E7D32`) are paired with matching 10-15% tint backgrounds to ensure immediate, error-free classification under emergency room conditions.

## Typography

Typography prioritizes maximum distance legibility, optical clarity, and cognitive comfort:

- **Headlines & Ticket Numbers (`lexend`)**: Engineered to enhance reading speed and reduce visual ambiguity. Its open counters and distinct character shapes ensure ticket codes (e.g., `EM-049`, `CONS-12`) remain instantly legible across wide hospital waiting lounges and on high-mounted LED/LCD TV monitors.
- **Body & Controls (`manrope`)**: A geometric and modern workhorse sans-serif offering neutral, professional balance for patient vitals, medical history, triage notes, and desk interface tables.
- **Display Scales**: Dedicated large-scale typography tokens (`display-ticket`, `display-room`) cater specifically to wall-mounted calling totems and digital signage, scaling down gracefully on staff tablet terminals and mobile patient check-in interfaces.

## Layout & Spacing

This design system uses an **8-point spatial grid** combined with a flexible multi-tier layout structure:

- **Public Display & Totem Layout**: A rigid, split-panel view. The active callout (Current Ticket & Counter/Consultório) consumes a minimum of 60% viewport width, with an adjacent vertical feed displaying the upcoming queue history. Margins are fixed at `space-2xl` (`3rem`) to prevent boundary clipping on varied monitor bezels.
- **Clinical Triage Workspace**: A 12-column responsive fluid grid with `1.5rem` (`space-lg`) gutters. Dense triage tables and patient charts maintain an 8px vertical cadence with compact 48px row heights to maximize visible patient capacity without scrolling.
- **Breakpoints**:
  - **Mobile / Patient PWA (< 768px)**: 4 columns, single-stack cards, sticky bottom action bar for primary actions.
  - **Tablet / Doctor Station (768px - 1199px)**: 8 columns, master-detail side panel layout.
  - **Desktop / Large Display (1200px+)**: 12 columns, fixed sidebar triage filters with dynamic queue boards and high-visibility status zones.

## Elevation & Depth

Visual hierarchy uses a refined **tonal layering and ambient boundary** approach rather than heavy, artificial drop shadows:

- **Base Layer (Level 0)**: The global canvas sits on `surface-soft` (`#F8FAF9`).
- **Cards & Data Modules (Level 1)**: Pure white (`#FFFFFF`) surfaces defined with a single hairline boundary `1px solid #E2E8E5` and an ultra-subtle ambient shadow: `box-shadow: 0 1px 3px rgba(26, 36, 33, 0.04), 0 1px 2px rgba(26, 36, 33, 0.02)`.
- **Calling Totem / Active Ticket Popout (Level 2)**: For tickets currently being rung, an elevated pulse card uses a soft green-tinted halo: `box-shadow: 0 10px 25px -5px rgba(46, 125, 50, 0.12), 0 8px 10px -6px rgba(46, 125, 50, 0.08)`.
- **Modals & Emergency Overlays (Level 3)**: Raised popovers use `box-shadow: 0 20px 25px -5px rgba(26, 36, 33, 0.15), 0 8px 10px -6px rgba(26, 36, 33, 0.1)` over a 40% opacity darkened green-neutral backdrop (`rgba(26, 36, 33, 0.4)`).

## Shapes

The design system adopts a **Rounded (`2`)** shape language, communicating safety, modern healthcare comfort, and approachable digital ergonomics:

- **Inputs, Buttons, and Data Cells**: Base corner radius is `0.5rem` (`8px`), balancing clinical precision with ergonomic softness.
- **Panels, Patient Cards, and Totem Modules**: Extended corner radius of `1rem` (`16px`) creates clean card silhouettes on large visual displays.
- **Triage Status Badges & Chips**: Fully pill-shaped (`9999px`) to emphasize their role as distinct, non-interactive medical classifications.

## Components

### Buttons
- **Primary ("Chamar Próximo", "Confirmar")**: Background `#1B5E20`, text `#FFFFFF`, radius `8px`, height `48px` (touch friendly). Hover: `#0D3C13`. Focus: ring `3px solid #C8E6C9`.
- **Secondary**: Outlined with `1.5px solid #2E7D32`, background `transparent`, text `#2E7D32`. Hover: background `#E8F5E9`.
- **Destructive/Emergency Action**: Background `#C62828`, text `#FFFFFF`. Hover: `#8E0000`.

### Priority Badges (Triage Indicators)
- **Emergência (Prio 1)**: Background `#FFEBEE`, text `#C62828`, border `1px solid rgba(198, 40, 40, 0.3)`. Font: `label-sm`, bold uppercase, pill-shaped.
- **Urgência (Prio 2)**: Background `#FFF8E1`, text `#F57F17`, border `1px solid rgba(245, 127, 23, 0.3)`.
- **Não Urgente (Prio 3)**: Background `#E8F5E9`, text `#2E7D32`, border `1px solid rgba(46, 125, 50, 0.3)`.

### Ticket Calling Card (Totem & TV Display)
- High-contrast pure white container (`#FFFFFF`) with a left border indicator (6px width) matching the priority level color.
- Displays ticket code in `display-ticket` (`96px`), patient name or masked ID in `headline-md`, and consulting room/desk in `display-room` (`56px`) with a green accent pill background `#E8F5E9`.

### Input Fields & Search Bars
- Background `#FFFFFF`, height `44px`, border `1px solid #D1DBD5`, radius `8px`.
- Text `#1A2421`, placeholder `#7D8A85`.
- Focus state: border `#2E7D32` with a `0 0 0 3px #E8F5E9` focus ring.

### Data Tables (Triage Queue)
- Header: `#F1F5F2` background, text `#4A5568`, typography `label-sm`.
- Rows: `#FFFFFF` background, border-bottom `1px solid #E2E8E5`. Alternating hover background `#F8FAF9`.
- Status, wait time elapsed, and quick call actions grouped within individual row modules.

### Checkboxes & Radios
- Size `20px x 20px`, border `2px solid #D1DBD5`, radius `4px` (checkbox) or `50%` (radio).
- Checked: background `#1B5E20`, border `#1B5E20`, checkmark in `#FFFFFF`.