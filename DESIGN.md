---
name: Midnight Value
colors:
  surface: '#051424'
  surface-dim: '#051424'
  surface-bright: '#2c3a4c'
  surface-container-lowest: '#010f1f'
  surface-container-low: '#0d1c2d'
  surface-container: '#122131'
  surface-container-high: '#1c2b3c'
  surface-container-highest: '#273647'
  on-surface: '#d4e4fa'
  on-surface-variant: '#d8c3ad'
  inverse-surface: '#d4e4fa'
  inverse-on-surface: '#233143'
  outline: '#a08e7a'
  outline-variant: '#534434'
  surface-tint: '#ffb95f'
  primary: '#ffc174'
  on-primary: '#472a00'
  primary-container: '#f59e0b'
  on-primary-container: '#613b00'
  inverse-primary: '#855300'
  secondary: '#4edea3'
  on-secondary: '#003824'
  secondary-container: '#00a572'
  on-secondary-container: '#00311f'
  tertiary: '#ffbbbe'
  on-tertiary: '#67001b'
  tertiary-container: '#ff919a'
  on-tertiary-container: '#8c0028'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#ffddb8'
  primary-fixed-dim: '#ffb95f'
  on-primary-fixed: '#2a1700'
  on-primary-fixed-variant: '#653e00'
  secondary-fixed: '#6ffbbe'
  secondary-fixed-dim: '#4edea3'
  on-secondary-fixed: '#002113'
  on-secondary-fixed-variant: '#005236'
  tertiary-fixed: '#ffdadb'
  tertiary-fixed-dim: '#ffb2b7'
  on-tertiary-fixed: '#40000d'
  on-tertiary-fixed-variant: '#92002a'
  background: '#051424'
  on-background: '#d4e4fa'
  surface-variant: '#273647'
typography:
  display-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 44px
  display-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 24px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  body-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '400'
    lineHeight: 16px
  numeric-hero:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  numeric-data:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '600'
    lineHeight: 20px
  label-md:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '500'
    lineHeight: 14px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1rem
  margin: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 0.75rem
  space-lg: 1.25rem
  space-xl: 1.75rem
---

## Brand & Style
The design system embodies "Midnight FinTech"—a refined, disciplined aesthetic tailored specifically for disciplined dollar-cost averaging (DCA) and long-term value investors. Unlike retail trading platforms engineered for dopamine loops and aggressive speculation, this UI conveys quiet confidence, deliberate pacing, and stoic financial stewardship.

The visual ethos blends **Refined Dark Minimalism** with **Tactile Surface Craft**:
- **Atmosphere**: Deep midnight slates eliminate visual fatigue during deep-dive fundamental research.
- **Materiality**: Elevated cards feature low-profile, hairline luster borders (1px) evoking matte precision watch dials or high-end financial hardware.
- **Accents**: Warm amber and harvest gold suggest compound growth and patience, abandoning harsh synthetic neons.
- **Tone**: Objective, unhurried, and institutional. Every element prioritizes clarity over urgency.

## Colors
The color hierarchy is calibrated for sustained analytical focus, maintaining strict contrast without visual vibration.

- **Background Canvas**:
  - `bg-root`: `#0B0E14` (Deep obsidian base canvas)
  - `bg-surface-subtle`: `#121824` (Grouped section backing)
  - `bg-surface`: `#161F30` (Primary container card fill)
  - `bg-surface-elevated`: `#1E293B` (Floating bottom sheets, dialogs, active states)
- **Borders & Dividers**:
  - `border-hairline`: `#2A374E` (1px subtle specular border for dark surfaces)
  - `border-subtle`: `#1E293B` (Divider lines within lists and forms)
- **Primary & Growth (Harvest Gold)**:
  - `primary`: `#F59E0B` (Amber gold for key action milestones, time-horizon indicators)
  - `primary-pressed`: `#D97706` (Deeper amber for interactive pressed states)
  - `primary-subtle`: `rgba(245, 158, 11, 0.12)` (Tinted container background for badges)
- **Financial Status (Controlled Yields)**:
  - `gain-emerald`: `#10B981` (Disciplined muted emerald for positive long-term return)
  - `gain-emerald-light`: `#34D399` (Secondary metrics and chart gradients)
  - `loss-rose`: `#F43F5E` (Gentle brick-rose for drawdowns and risk flags, devoid of alarming glare)
  - `loss-rose-light`: `#FB7185` (Negative secondary indicator)
- **Typography & Neutral Tokens**:
  - `text-primary`: `#F8FAFC` (Ivory white for primary values and headers)
  - `text-secondary`: `#94A3B8` (Cool muted silver-gray for secondary descriptors)
  - `text-muted`: `#64748B` (Tertiary indicators, disabled states, micro-captions)

## Typography
Typographic discipline underpins the credibility of financial tracking. 

- **Numeric Rigor**: All numeric values (yields, asset balances, share allocations, P/E multiples) must render with `font-feature-settings: "tnum" 1, "cv01" 1` enabled. This guarantees tabular figure alignment across columns and prevents jitter during real-time balance redraws.
- **Editorial Voice**: `Plus Jakarta Sans` delivers a contemporary, structured poise to portfolio overview cards and investment thesis headers. `Inter` provides neutral, hyper-legible body copy suited for fundamental analysis memos and qualitative filings.
- **Hierarchy Rules**:
  - Always pair large valuation headlines (`display-lg-mobile` or `numeric-hero`) with a micro-label (`label-sm` in `text-muted` uppercase) anchored above the value.
  - Sub-indicators (e.g., benchmark comparison tags) rely strictly on `numeric-data` to preserve vertical cadence across device boundaries.

## Layout & Spacing
The layout architecture focuses on vertical modularity for handheld single-column operations, expanding to multi-column data views on larger devices.

- **Mobile Rhythm (Base: 4px/8px)**:
  - Outer screen edge margin: `16px` (`margin`).
  - Gap between stacked portfolio cards: `12px` to `16px`.
  - Internal card padding: `16px` (compact summary) to `20px` (hero aggregate card).
- **Responsive Adaptations**:
  - **Mobile (<640px)**: Strict 1-column stack. Sticky primary bottom actions for scheduled DCA authorizations.
  - **Tablet (640px–1024px)**: 2-column asymmetric split (left: wealth trajectory & DCA engine; right: moat metrics & research logs). Margin broadens to `24px`, gutter becomes `16px`.
  - **Desktop/Large (>1024px)**: 12-column grid capped at a maximum width of `1200px` centered, reserving gutters of `24px`.

## Elevation & Depth
Depth in this system avoids blurry drop-shadows that mimic daylight or retail playfulness. Visual stratification is achieved through **Tonal Tiers** and **Specular Hairlines**:

- **Tier 0 (Canvas Base)**: `#0B0E14` (Empty void).
- **Tier 1 (Resting Cards & Memos)**: `#161F30` surface backed by a solid 1px border of `#2A374E`. No box-shadow needed; the edge provides crisp architectural contrast.
- **Tier 2 (Hero Holdings & Floating Bar)**: `#1E293B` surface with a subtle directional top-edge highlight (`border-top: 1px solid rgba(245, 158, 11, 0.35)`) and an ambient tinted drop: `box-shadow: 0 8px 24px -4px rgba(0, 0, 0, 0.45)`.
- **Tier 3 (Modals & DCA Execution Sheets)**: `#1E293B` elevated with backdrop blur (`backdrop-filter: blur(16px)` on the background scrim: `rgba(11, 14, 20, 0.75)`). Edge defined by `border: 1px solid rgba(148, 163, 184, 0.15)`.

## Shapes
Geometry is disciplined and architectural, striking an equilibrium between technical precision and tactile modernism.

- **Scale Application**:
  - `rounded-sm` (4px): Micro badges, tag borders, dividend mini-bars.
  - `rounded-md` (8px): Form input fields, segmented control switches, moat rating pills.
  - `rounded-lg` (16px): Core portfolio metric cards, research log containers, bottom sheet top edges.
  - `rounded-xl` (24px): Floating utility action modules and key financial milestone highlights.

## Components

### 1. Asset Overview & Trajectory Card (Hero)
- **Background**: Multi-layered fill utilizing `#161F30` with an imperceptible radial gradient originating from top-right (`rgba(245, 158, 11, 0.05)`).
- **Structure**: 
  - Primary headline shows cumulative net worth in `numeric-hero` (`#F8FAFC`).
  - Secondary row pairs the historic annual return (CAGR) with an emerald badge (`#10B981` text over `rgba(16, 185, 129, 0.12)` fill).
  - Footer provides an integrated compound interest sparkline with a hairline stroke and zero-fill opacity to prioritize trend over noise.

### 2. Systematic DCA Progress Bar (定投纪律条)
- **Base Track**: 6px height, rounded ends, filled with `#1E293B`.
- **Active Progress**: Solid `#F59E0B` to indicate completed recurring cycles.
- **Execution Indicator**: Pulsing 10px diamond pin marking the next execution window, with next buy-date label (`body-sm`) aligned right.

### 3. Investment Thesis Journal Card (长线逻辑手记)
- **Purpose**: Encourages thesis-driven investing rather than reactive news consumption.
- **Style**: Textured slate background (`#161F30`), bordered with `#2A374E`. Left edge features an inset 2px accent rule (`#F59E0B`).
- **Typography**: Header in `headline-sm`, followed by bulleted foundational pillars (e.g., Pricing Power, Capital Allocation) rendered in `body-md` (`#94A3B8`).

### 4. Economic Moat Rating Chips (护城河评级标签)
- **Visuals**: Compact badges with 6px horizontal padding, 2px vertical padding, rounded to 4px.
- **Variants**:
  - *Wide Moat*: Amber outline (`#F59E0B`), warm gold text, background `rgba(245, 158, 11, 0.1)`.
  - *Narrow Moat*: Cool slate outline (`#94A3B8`), neutral white text, background `rgba(148, 163, 184, 0.08)`.
  - *No Moat*: Translucent border (`#2A374E`), muted gray text (`#64748B`).

### 5. Dividend & Return Micro-Bar Calendar
- **Layout**: 12-column horizontal sequence representing calendar months.
- **Bar Styling**: Vertical bars (4px width, 2px top radius). Empty months marked with single 2px dots (`#1E293B`).
- **Data States**: Standard accumulation in `#34D399`; special or extra dividend yield marked with a harvest gold cap (`#F59E0B`).

### 6. Interactive Form Elements & Buttons
- **Primary Action (Confirm Cadence / Rebalance)**: Deep amber button (`#F59E0B`) with high-contrast obsidian text (`#0B0E14`), weight 600, height 48px, radius 8px.
- **Secondary Action**: Bordered ghost button (`#2A374E` border, `#F8FAFC` text) hovering to `#1E293B`.
- **Inputs**: Flat `#121824` background, `border: 1px solid #2A374E`, focused border transitioning smoothly to `#F59E0B` without high-glow fuzz.