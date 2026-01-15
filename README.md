# Dashboard with Sidebar

A responsive dashboard layout with a sidebar featuring FlyonUI Tailwind CSS components.

## Features

- **Responsive Sidebar**: Collapses on mobile devices, expands on desktop
- **Main Menu Section**: Contains "Dashboard" and "Project" items
- **FlyonUI Integration**: Uses FlyonUI Tailwind CSS component library
- **Iconify Icons**: Modern icon system with Tabler icons
- **Collapsible Sections**: Interactive menu sections that expand/collapse
- **Clean Design**: Modern, minimalist interface with proper spacing

## Sidebar Structure

1. **Main Menu Separator**
   - Dashboard (with layout-dashboard icon)
   - Project (with folder icon)

2. **Apps Section** (Collapsible)
   - Chat
   - Calendar

3. **Settings**

4. **Account Separator**
   - Sign In
   - Sign Out

5. **Miscellaneous Separator**
   - Support
   - Documentation

## Technologies Used

- HTML5
- Tailwind CSS
- FlyonUI (Tailwind CSS component library)
- Iconify (for icons)
- Vanilla JavaScript for interactivity

## How to Use

1. Open `index.html` in a web browser
2. On mobile: Tap the menu button (top-left) to toggle sidebar
3. On desktop: Sidebar is always visible
4. Click "Apps" to expand/collapse the apps section
5. Click any menu item to navigate (links are placeholder #)

## Customization

To customize the sidebar:

1. **Add new menu items**: Copy the `<li>` structure from existing items
2. **Change icons**: Use any Iconify icon name (e.g., `tabler:home`)
3. **Add separators**: Use `<div class="divider text-base-content/50 py-6 after:border-0">Section Name</div>`
4. **Modify colors**: Update Tailwind CSS classes in the HTML

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

MIT