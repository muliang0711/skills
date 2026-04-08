---
name: frontend-design
description: Create distinctive, production-grade frontend interfaces with high design quality. Use this skill when the user asks to build or improve web pages, components, dashboards, landing pages, HTML/CSS layouts, React views, or any UI that needs design work, polish, or a visual refresh. Prefer this skill for frontend styling, redesigns, and new interface implementation.
metadata:
  short-description: Build distinctive frontend UI
---

# Frontend Design

Build real frontend code with a clear visual point of view. Favor intentional design over generic layouts.

## Workflow

1. Identify the target surface: page, component, dashboard, artifact, or full app screen.
2. Preserve the existing design system when one already exists. Do not force a new aesthetic into an established product.
3. If the project has no strong visual language, choose one before coding and keep it consistent.
4. Implement directly in the repo's framework and conventions.
5. Verify responsive behavior, interaction states, and basic accessibility.

## Art Direction

Before editing code, decide:

- Purpose: what the interface helps the user do.
- Audience: who uses it and what tone fits them.
- Constraints: framework, performance, accessibility, and existing tokens or components.
- Signature: one memorable visual idea that gives the UI identity.

Strong directions can be minimal, editorial, industrial, playful, brutalist, refined, retro, or highly expressive. The important part is commitment and consistency.

## Design Rules

- Use purposeful typography. Avoid generic defaults unless the product already uses them.
- Use CSS variables or existing design tokens for colors, spacing, radius, and shadows.
- Build hierarchy with spacing, contrast, scale, and alignment before adding decoration.
- Use motion sparingly but intentionally: page-load sequencing, hover feedback, and state transitions should support the design rather than distract from it.
- Prefer backgrounds with depth or texture when the concept needs it; avoid flat, empty surfaces by default.
- Match implementation complexity to the concept. Minimal interfaces need restraint; expressive interfaces need enough detail to feel finished.

## Avoid

- Generic AI-looking layouts and interchangeable SaaS sections.
- Overused purple-on-white gradients unless the product already uses them.
- Default font stacks with no clear reason.
- Decorative effects that do not support the chosen direction.
- Random inconsistency between cards, spacing, corner radius, or motion timing.

## Implementation Notes

- For React work, follow the repo's current patterns and component structure.
- For static HTML/CSS, keep the file self-contained and readable.
- Reuse existing components when practical; create new abstractions only when repetition justifies them.
- Include concise comments only where the design logic would otherwise be hard to infer.

## Quality Bar

- Works on desktop and mobile.
- Has clear hover, focus, active, and disabled states where relevant.
- Maintains acceptable contrast and keyboard usability.
- Feels deliberate, not templated.
