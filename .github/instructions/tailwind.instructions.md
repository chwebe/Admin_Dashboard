---
applyTo: "**/*.html,**/*.tsx,**/*.jsx,**/*.vue"
---
# Tailwind CSS Coding Standards

## General Guidelines
- Use Tailwind utility classes for all styling; avoid custom CSS unless necessary.
- Prefer semantic HTML elements and accessible markup.
- Group related Tailwind classes together (layout, spacing, color, typography).
- Use responsive and dark mode variants as needed.
- Avoid using arbitrary values unless required for design consistency.
- Use @apply in CSS only for repeated utility patterns.

## Example
```html
<button class="bg-blue-600 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded">
  Button
</button>
```

## Comments
- Add comments to explain non-obvious class combinations or design choices.

You can further customize this file to match your team's specific Tailwind conventions. Place it in .github/instructions/ and ensure your VS Code Copilot settings enable instruction files.
