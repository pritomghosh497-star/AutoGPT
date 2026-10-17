## 2026-10-17 - Add missing ARIA labels to icon-only buttons
**Learning:** The `<Button>` component in this codebase automatically generates a tooltip when `variant="icon"` is used, but only if an `aria-label` is provided. Therefore, missing `aria-label`s on icon-only buttons not only break screen reader accessibility, but also hide visual tooltips for sighted users.
**Action:** Always ensure `aria-label` is provided for icon-only buttons. If a visual tooltip is not desired but an `aria-label` is still needed for accessibility, explicitly pass `withTooltip={false}`.
