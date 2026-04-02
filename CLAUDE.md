# Logan Brands — Site Standards

## Mobile

### Hamburger Menu
Every project must include a hamburger menu for mobile devices. On screens ≤900px (or the project's mobile breakpoint), the desktop nav links should be hidden and replaced with a hamburger button that opens a fullscreen or drawer-style menu overlay containing all the same navigation links.

Requirements:
- Desktop nav links hidden on mobile
- Hamburger button visible on mobile
- Tapping a link closes the menu
- Body scroll locked while menu is open

### Mobile Cursor
Touch devices should suppress the custom cursor:
```css
@media (hover: none) and (pointer: coarse) {
  * { cursor: none !important; }
}
```
