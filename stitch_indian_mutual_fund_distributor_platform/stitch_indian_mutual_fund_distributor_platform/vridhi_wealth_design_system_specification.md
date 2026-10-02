# Vridhi Wealth — Master Design System Specification & Token Architecture
**Platform:** Indian Mutual Fund Distribution (MFD) & Wealth Management Platform (Investor & Distributor/Admin Portals)  
**Target Stack:** Next.js, React, TypeScript, Tailwind CSS, Lucide React  
**Compliance Standard:** AMFI & SEBI Regulatory Alignment

---

## 1. Color Palette & Semantic Tokens

### 1.1 Brand & Fiduciary Primaries
- `primary-900` (`#071F18`): Deepest Forest Slate — high-contrast text, dark accents, footer ground.
- `primary-800` (`#0D2F24`): **Primary Brand Color** — institutional fiduciary emerald forest. Used for primary CTAs, active states, key branding elements.
- `primary-700` (`#154637`): Primary Hover state.
- `primary-600` (`#1F5E4B`): Secondary brand highlights and active pill backgrounds.
- `primary-100` (`#E6F4EE`): Light tint for active tabs, selected states, and badge backgrounds.
- `primary-50` (`#F2F9F5`): Ultra-subtle tint for table highlight rows and banner tints.

### 1.2 Accents & Secondary Colors
- `accent-emerald` (`#10B981`): Vibrant growth & positive returns indicator, compound interest line charts, verified checks.
- `accent-emerald-dark` (`#059669`): Hover / contrast text on light green badges.
- `secondary-navy` (`#1E293B`): Deep slate navy for secondary buttons, dark badges, and icon backdrops.
- `secondary-slate` (`#334155`): Neutral secondary emphasis.

### 1.3 Surface & Canvas Neutrals
- `bg-canvas` (`#F8FAFC`): Clean, warm-tinted cool gray canvas (reduces glare vs pure white).
- `bg-surface` (`#FFFFFF`): Pure white card surface, modal surface, and input container.
- `bg-surface-elevated` (`#FFFFFF`): Elevated cards with `box-shadow: 0 4px 20px -2px rgba(13, 47, 36, 0.06)`.
- `bg-subtle` (`#F1F5F9`): Inactive inputs, disabled pills, subtle metric wells.
- `bg-border` (`#E2E8F0`): Default crisp border for cards and input boundaries.
- `bg-border-light` (`#EEF2F6`): Inner table row dividers and list borders.

### 1.4 Text Colors
- `text-primary` (`#0F172A`): Slate 900 — Maximum readability for headers, values, and client names.
- `text-secondary` (`#475569`): Slate 600 — Informational body text, labels, metadata.
- `text-tertiary` (`#94A3B8`): Slate 400 — Disclaimers, timestamp captions, placeholder text.
- `text-inverse` (`#FFFFFF`): High-contrast white text on dark cards and primary buttons.
- `text-brand` (`#0D2F24`): Primary brand text for highlighted titles and links.

### 1.5 Semantic Status & Financial Return Colors
- **Success / Positive Growth**:
  - `success-base` (`#059669` / `#10B981`): Green for positive CAGR, XIRR (`+18.2%`), KYC Verified (`KYC OK`), SIP Active.
  - `success-bg` (`#ECFDF5`): Soft mint badge and alert background.
  - `success-border` (`#A7F3D0`): Border for success notifications and valid states.
- **Warning / Pending Action**:
  - `warning-base` (`#D97706`): Amber for Expiring Mandates, DigiLocker Incomplete, Moderate Risk.
  - `warning-bg` (`#FFFBEB`): Subtle yellow warning container.
  - `warning-border` (`#FDE68A`): Warning perimeter border.
- **Error / Failure / Negative**:
  - `error-base` (`#DC2626`): Red for Auto-Debit Failure, Negative Returns (`-2.4%`), Very High Risk, Form Validation.
  - `error-bg` (`#FEF2F2`): Error alert background.
  - `error-border` (`#FECACA`): Error card and input highlight border.
- **Info / Fiduciary Neutral**:
  - `info-base` (`#2563EB`): Blue for BSE StAR MF sync status, SEBI circular notifications, informational tooltips.
  - `info-bg` (`#EFF6FF`): Informational card container.

---

## 2. Typography & Numerical Formatting

**Primary Font:** `Plus Jakarta Sans` (Geometric, friendly, highly legible)  
**Secondary/Tabular Numbers Font:** `Inter` / `Plus Jakarta Sans` with `font-variant-numeric: tabular-nums lining-nums`

### Scale Hierarchy
- **H1 (Screen Title / Primary Hero):** 28px – 32px | Bold (700) | Line-height 1.2 | Tracking `-0.02em`
- **H2 (Card Header / Major Section):** 20px – 24px | SemiBold (600) | Line-height 1.3 | Tracking `-0.015em`
- **H3 (Sub-section / Modal Title):** 16px – 18px | SemiBold (600) | Line-height 1.4 | Tracking `-0.01em`
- **Body Regular:** 14px – 15px | Regular (400) / Medium (500) | Line-height 1.5
- **Small Text / Captions / Disclaimers:** 11px – 12px | Medium (500) | Line-height 1.4 | Color: `text-tertiary`
- **Numbers / Metrics (KPI Metric Values):** 28px – 36px | Bold (700) | Tabular Numbers (e.g. `₹48.65 Cr`, `₹28,45,210`)
- **Financial Return Badges (XIRR / CAGR):** 13px – 14px | SemiBold (600) | Line-height 1 | Strict prefix `+` or `-`

---

## 3. UI Component System Standards

1. **Buttons:** Primary (`#0D2F24` with hover transition), Secondary (White with border `#E2E8F0`), Tertiary/Ghost, Destructive, and Icon Action buttons with ripple/focus rings.
2. **Inputs & Form Controls:** Standard 42px height, 8px border radius, subtle `#E2E8F0` border, active emerald focus ring (`ring-2 ring-[#0D2F24]/20 border-[#0D2F24]`), clear error validation state with helper text.
3. **Dropdowns & Selectors:** Custom clean select menus with trailing chevron, clear label hierarchy, and keyboard navigable states.
4. **Search Boxes:** Global search input with shortcut hint (`Ctrl+K`), search icon prefix, and clear button.
5. **Tabs:** Pill-style segmented tabs (`bg-slate-100` track with active white card shadow) and underline border tabs for sub-navigation.
6. **Data Tables:** Clean 48px row height, sticky header with subtle uppercase tracking, zebra hover, responsive numeric column alignment (`text-right` for Indian currency & percentages).
7. **Badges & Tags:** Micro badges with 4px border radius or full pill: Success (`KYC Verified`), Warning (`Action Required`), Info (`HNI`), Category (`Flexi Cap`), and SEBI Risk-o-meter badges.
8. **Financial Charts:** Standardized SVG charts with smooth cubic splines, comparison benchmark dashed lines, green gradient fill for positive growth, and clean axis ticks.
9. **Feedback States:** Empty states with friendly financial vector illustrations, skeleton loading shimmer cards, error failure alerts with retry triggers, and crisp toast notifications.
10. **Modals & Drawers:** Clean backdrop blur (`backdrop-blur-sm bg-slate-900/40`), centered rounded container (`rounded-2xl`), dismiss button, clear sticky action footer.
