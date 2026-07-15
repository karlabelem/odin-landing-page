# Landing Page — CSS Practice

A responsive landing page built as part of Oding Project curriculum, focused on practicing core CSS layout principles — particularly Flexbox.

## 🎯 Goals
This project was built to practice:
- Structuring semantic HTML with clear parent/child relationships
- Flexbox layout (`flex-direction`, `justify-content`, `align-items`, `gap`)
- The difference between `margin` and `padding`
- Nesting flex containers to control layout at multiple levels
- Debugging default browser styles (e.g. default `<p>` margins)
- Building reusable, repeated components (card layouts)

## 🧱 Sections
- **Header** — logo and navigation links
- **Hero** — headline, subtext, CTA button, and image placeholder
- **Information Section** — repeating card layout (icon/border box + caption)
- **Testimonial** — centered quote block with attribution
- **Call to Action** — signup prompt with button
- **Footer** — copyright line

## 🛠️ Built With
- HTML5
- CSS3 (Flexbox)

## 📚 What I Learned
- How `flex-direction: row` vs `column` flips the meaning of `justify-content` and `align-items` (main axis vs. cross axis)
- Why `justify-content` and `gap` can conflict when there's leftover space to distribute
- How default flex behavior (`align-items: stretch`) can force child elements to fill container height unexpectedly
- How browser default margins (especially on `<p>` tags) can silently affect spacing
- When to group elements into a wrapper div (parent) vs. keeping them as siblings, based on the layout relationship needed
