---
name: Vridhi Wealth
colors:
  surface: '#f8f9ff'
  surface-dim: '#cbdbf5'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e5eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d3e4fe'
  on-surface: '#0b1c30'
  on-surface-variant: '#414845'
  inverse-surface: '#213145'
  inverse-on-surface: '#eaf1ff'
  outline: '#717974'
  outline-variant: '#c1c8c3'
  surface-tint: '#446558'
  primary: '#001911'
  on-primary: '#ffffff'
  primary-container: '#0d2f24'
  on-primary-container: '#759889'
  inverse-primary: '#aacebe'
  secondary: '#904d00'
  on-secondary: '#ffffff'
  secondary-container: '#fe932c'
  on-secondary-container: '#663500'
  tertiary: '#00190e'
  on-tertiary: '#ffffff'
  tertiary-container: '#00301e'
  on-tertiary-container: '#00a472'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#c6ebda'
  primary-fixed-dim: '#aacebe'
  on-primary-fixed: '#002117'
  on-primary-fixed-variant: '#2c4d41'
  secondary-fixed: '#ffdcc3'
  secondary-fixed-dim: '#ffb77d'
  on-secondary-fixed: '#2f1500'
  on-secondary-fixed-variant: '#6e3900'
  tertiary-fixed: '#6ffbbe'
  tertiary-fixed-dim: '#4edea3'
  on-tertiary-fixed: '#002113'
  on-tertiary-fixed-variant: '#005236'
  background: '#f8f9ff'
  on-background: '#0b1c30'
  surface-variant: '#d3e4fe'
typography:
  display:
    fontFamily: Plus Jakarta Sans
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.015em
  headline-lg-mobile:
    fontFamily: Plus Jakarta Sans
    fontSize: 26px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Plus Jakarta Sans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Plus Jakarta Sans
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  title-lg:
    fontFamily: Plus Jakarta Sans
    fontSize: 18px
    fontWeight: '600'
    lineHeight: 26px
  title-md:
    fontFamily: Inter
    fontSize: 16px
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
  label-md:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '500'
    lineHeight: 18px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.04em
  metric-val:
    fontFamily: Inter
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 34px
    letterSpacing: -0.02em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 2rem
  margin-mobile: 1rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style

This design system establishes a high-trust, institutional, yet fundamentally modern wealth management experience tailored for Indian investors and AMFI-registered Mutual Fund Distributors (MFDs). Unlike gamified equity trading applications optimized for high-frequency transactions and speculative churn, this platform centers on compounding, disciplined Systematic Investment Plans (SIPs), goal-based financial roadmaps, and fiduciary stewardship.

The aesthetic fuses **Modern Institutional Precision** with refined **Fintech Clarity**:
- **Dignity & Permanence:** Deep heritage forest hues communicate stability, longevity, and regulatory compliance.
- **Data Clarity:** Strict hierarchy, deliberate white space, tabular numerals, and subdued structural lines replace distracting visual noise.
- **Reassurance & Fiduciary Trust:** Institutional accreditations (AMFI registration, BSE StAR MF, NSE NMF II execution backbones) and statutory guardrails (SEBI Risk-o-meter gauges) are treated as first-class architectural elements rather than footer disclaimers.

## Colors

The system uses a calibrated palette reflecting financial resilience, regulatory compliance, and clarity across data-dense portfolios.

### Role Assignments & Application

- **Primary (`#0D2F24` — Deep Heritage Forest):** Anchors core brand presence, primary actions, high-level navigation, and prominent asset totals. It conveys institutional gravitas over transient tech hype.
- **Secondary (`#D97706` — Heritage Brass / Gold):** Reserved for institutional trust seals, AMFI accreditation badges, milestone targets, and privileged advisory tier indicators. It signals value and stewardship without descending into garish luxury.
- **Tertiary (`#10B981` — Modern Emerald):** Applied selectively to positive capital flow, annualized gains (+XIRR, CAGR), active SIP status pills, and forward trajectory graphs. Paired with soft mint tint (`#D1FAE5`) for low-fatigue badge containers.
- **Negative / Alert (`#EF4444` — Coral Crimson):** Reserved for capital depreciation, missed mandates, KYC rejections, and "Very High" risk designations. Paired with muted crimson surface fills (`#FEE2E2`).
- **Neutrals (`#F8FAFC` to `#0F172A`):** Canvas foundation rests on pristine slate-tinted white (`#F8FAFC`), supporting crisp boundary definitions (`#E2E8F0`) and elevated white tiles (`#FFFFFF`). Body copy resolves to `#334155` for reduced eye strain during extended analytical reading, reserving `#0F172A` for primary data points and headings.

## Typography

The typographic system utilizes **Plus Jakarta Sans** for structural headlines and **Inter** for all analytical data, metric values, and textual UI.

### Number Formatting & Tabular Integrity
- All numeric figures representing currency values (e.g., `₹24,50,000`), percentage returns (`+14.8% XIRR`), and folio units must enable OpenType tabular lining figures (`font-variant-numeric: tabular-nums lining-nums`). This guarantees columnar alignment across ledger views, performance breakdowns, and distributor scheme trackers.
- Rupee symbols (`₹`) maintain the baseline font metric weight of their accompanying digit string rather than standard punctuation scale.
- Section tags, regulatory caveats, and category pills utilize `label-sm` with subtle uppercase tracking to distinguish static taxonomy from dynamic investor metrics.

## Layout & Spacing

The layout is built around a structured 12-column responsive fluid grid designed to support complex dual-audience views: compact client management for distributors and high-clarity dashboard summaries for retail investors.

### Form Factor Behavior
- **Desktop (1280px+):** 12-column grid, max-width bounded container at 1440px with `margin: 2rem` canvas inset. Sidebar navigations lock to fixed 260px or 80px rail layouts, leaving the main content region fluid across 12 columns with `gutter: 1.5rem`.
- **Tablet (768px – 1279px):** 8-column layout. Data-heavy multi-column performance metrics collapse into two-row structured pairs. Section margins compress to `1.5rem`.
- **Mobile (< 768px):** 4-column layout with `margin-mobile: 1rem` and `gutter-mobile: 1rem`. Multi-column portfolio cards collapse into stacked atomic rows with single-finger tap zones along the vertical reading axis.

### Spacing Cadence
Component nesting adheres strictly to the 4px baseline rhythm (`space-xs` to `space-xl`). Card internal padding standardizes to `space-lg` (24px) for desktop summary panels and `space-md` (16px) on mobile viewports.

## Elevation & Depth

This design system avoids theatrical 3D skeuomorphism and excessive drop shadows in favor of a crisp, quiet architectural depth model based on **Tonal Layering** and **Atmospheric Edge Pinning**.

### Surface Hierarchy
1. **Canvas (Base Level):** `#F8FAFC` (Slate Tint). The non-interactive foundational layer.
2. **Surface Default (Level 1):** `#FFFFFF` pure white cards with an edge-defining border (`1px solid #E2E8F0`). Subtle downward ambient shadow: `box-shadow: 0 1px 3px 0 rgba(15, 23, 42, 0.04), 0 1px 2px -1px rgba(15, 23, 42, 0.03)`.
3. **Surface Elevated / Hover (Level 2):** Elevated interactive elements (e.g., selectable Mutual Fund Scheme Card on focus, active quick-switch client drawer): `box-shadow: 0 10px 15px -3px rgba(13, 47, 36, 0.05), 0 4px 6px -4px rgba(13, 47, 36, 0.02)`, paired with border transition to `#CBD5E1`.
4. **Modal / Mandate Overlays (Level 3):** Fixed backdrop sheets (SIP execution approval, BSE/NSE net-banking authentication modals): Elevated with `box-shadow: 0 20px 25px -5px rgba(15, 23, 42, 0.1), 0 8px 10px -6px rgba(15, 23, 42, 0.05)`.

## Shapes

The design system maintains a **Rounded (Level 2)** profile throughout all surfaces and interactive controls, balancing contemporary fintech accessibility with established institutional structure.

- **Primary Cards & Modals:** Standardized to `rounded-lg` (16px / 1rem) for an approachable, contained appearance that softens heavy financial ledgers.
- **Buttons, Text Inputs, and Dropdowns:** Standardized to `rounded` (8px / 0.5rem) to reinforce functional precision, intentionality, and alignment within tight data grids.
- **Status Pills, AMFI Verification Tags, and Risk-o-meter Level Indicators:** Utilize full-pill radii (`rounded-full` / 9999px) to clearly differentiate meta-labels, status tags, and performance attributes from square interactive touch targets.

## Components

### Buttons
- **Primary Action (Invest Now, Create SIP, Authorize Mandate):** Solid `#0D2F24` fill, `#FFFFFF` text, 8px border-radius, font `label-md`. Hover state subtly transitions to `#164E3D`.
- **Secondary Action (View Factsheet, Compare Funds):** Transparent background, 1px border `#CBD5E1`, text `#0D2F24`. Hover transitions to `#F1F5F9`.
- **Destructive Action (Cancel SIP, Stop Mandate):** Subdued surface `#FEE2E2` with `#991B1B` text. Avoid aggressive solid red buttons to prevent accidental panic.

### Input Fields & Mandate Selectors
- Background `#FFFFFF`, border `1px solid #CBD5E1`, text `#0F172A`. Focused state uses an explicit outline of `2px solid #0D2F24` with zero drop-shadow bleed.
- **Currency Inputs:** Fixed prefix `₹` icon rendered in `#64748B` with tabular input values right-aligned or offset left-to-right. Support dynamic conversion hint subtext below field (e.g., "₹50,000 — Fifty Thousand Rupees").

### Financial Summary Cards
- White `#FFFFFF` base container with `space-lg` padding.
- Metric values use `metric-val` (`28px Inter Bold`, tabular nums).
- Include inline trend badges: e.g., `+18.4% XIRR` wrapped in `#D1FAE5` surface with `#065F46` bold text, accompanied by directional micro-arrows.

### Mutual Fund Scheme Cards
- Header houses fund house logo (36x36px, `rounded-md`), scheme nomenclature (`title-md`), and category badge (`Large Cap`, `Flexi Cap`, `ELSS Tax Saver`).
- Scheme performance grid: 3-column sub-layout displaying 1Y, 3Y, and 5Y annualized returns.
- **Risk-o-meter Gauge:** Standardized 6-tier indicator (Low, Low to Moderate, Moderate, Moderately High, High, Very High) represented via a compact segmented bar or badge using strict SEBI-prescribed chromatic steps, anchored by the current risk category in bold.

### Data Tables (Client Portfolios & Execution Logs)
- Headers in `label-sm`, uppercase, tracking `0.04em`, color `#64748B`, with thin divider lines (`#E2E8F0`).
- Alternating row interaction on hover using `#F8FAFC`.
- All financial metrics, units, and folio numbers align right; investor details, fund names, and status tags align left.
- Numeric data columns enforce tabular figures (`font-variant-numeric: tabular-nums`).

### Regulatory & Trust Badges
- **AMFI Registered MFD Badge:** Contained within a `#FEF3C7` border and fill, displaying deep brass typography (`#92400E`) with the registered ARN (Amfi Registration Number) cleanly surfaced.
- **Platform Execution Infrastructure:** Subtle secondary stamp with dual logos indicating BSE StAR MF / NSE NMF II order routing compliance.