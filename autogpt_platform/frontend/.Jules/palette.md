## 2024-10-16 - Add missing aria-label and title to icon-only buttons
**Learning:** Found an icon-only button without an aria-label in `EditNameDialog.tsx` which can be unhelpful for screen readers and sighted users who may not know what the pencil icon means without a title or tooltip.
**Action:** When adding new icon-only buttons, ensure they have an `aria-label` and `title` to provide context and accessible names.
