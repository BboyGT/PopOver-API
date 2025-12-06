# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.0.0] - 2025-12-06

### Added
- Initial release of Popover API Demo Playground
- Native Popover API implementation with automatic fallbacks
- CSS Anchor Positioning for contextual menus
- Six different popover variants:
  - Dropdown menu with navigation links
  - Tooltip with hover/focus triggers
  - Profile menu with avatar
  - Actions menu with vertical layout
  - Auto-dismissing notifications
  - Centered guided tour modal
- Full keyboard accessibility (Tab, Esc, Enter navigation)
- ARIA attributes for screen reader support
- Smooth CSS animations with `@starting-style`
- Responsive design for mobile, tablet, and desktop
- Feature detection and progressive enhancement
- Reset button to close all popovers
- Debug mode for development

### Features
- ✨ Popover API with `popover="auto"` and `popover="manual"` modes
- ⚓ CSS anchor positioning (when supported)
- 🎨 Dark theme with glassmorphism effects
- ♿ WCAG 2.1 Level AA accessibility compliance
- 📱 Mobile-first responsive layout
- 🔄 Automatic fallback for unsupported browsers
- 🎭 Backdrop overlay for modal popovers
- ⌨️ Complete keyboard navigation support

### Browser Support
- Chrome/Edge 114+ (full support)
- Safari 17+ (full support)
- Firefox (with fallbacks)
- All modern browsers (with progressive enhancement)

---

## [Unreleased]

### Planned
- [ ] Additional popover variants (dialog, mega menu)
- [ ] Dark/light theme toggle
- [ ] More animation presets
- [ ] Enhanced mobile gestures
- [ ] Improved fallback positioning logic
- [ ] Unit tests with Jest
- [ ] E2E tests with Playwright

---

[1.0.0]: https://github.com/your-username/popover-api-demo/releases/tag/v1.0.0