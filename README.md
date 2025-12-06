# Popover API Demo Playground

> An interactive demonstration of the native Popover API with anchor positioning, accessible keyboard navigation, and progressive enhancement.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

## 🎯 Overview

This project showcases modern web UI patterns using the native **Popover API**, featuring dropdown menus, tooltips, notifications, profile menus, and guided tours—all with smooth animations and full keyboard accessibility.

![Popover Demo Preview](https://via.placeholder.com/800x450/071021/6ee7b7?text=Popover+API+Demo)

## ✨ Features

- 🎨 **Native Popover API** - Uses the built-in browser Popover API with fallback support
- ⚓ **Anchor Positioning** - CSS anchor positioning for contextual menus (when supported)
- ♿ **Fully Accessible** - ARIA attributes, keyboard navigation (Tab, Esc), and focus management
- 🎭 **Smooth Animations** - CSS transitions with `@starting-style` for entrance/exit effects
- 📱 **Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- 🔄 **Progressive Enhancement** - Graceful fallbacks for browsers without native support
- 🎯 **Multiple Variants** - Dropdowns, tooltips, notifications, profile menus, and modal tours

## 🚀 Demo

[**View Live Demo**](https://your-username.github.io/popover-api-demo/) *(Update with your GitHub Pages URL)*

## 📋 Components Included

| Component | Type | Features |
|-----------|------|----------|
| **Dropdown Menu** | `popover="auto"` | Anchor positioned, auto-dismiss |
| **Tooltip** | `popover="manual"` | Hover/focus triggered, manual control |
| **Profile Menu** | `popover="auto"` | Right-aligned, avatar display |
| **Actions Menu** | `popover="auto"` | Vertical icon menu |
| **Notification** | `popover="manual"` | Auto-dismiss after 2s |
| **Guided Tour** | `popover="auto"` | Centered modal with backdrop |

## 🛠️ Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/popover-api-demo.git
cd popover-api-demo
```

### Run Locally

Simply open `index.html` in your browser:

```bash
# On macOS
open index.html

# On Linux
xdg-open index.html

# On Windows
start index.html
```

Or use a local development server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (http-server)
npx http-server

# Using PHP
php -S localhost:8000
```

Then navigate to `http://localhost:8000`

## 📖 Usage

### Basic Popover Pattern

```html
<!-- Button with popover trigger -->
<button popovertarget="my-popover" popovertargetaction="toggle">
  Open Menu
</button>

<!-- Popover content -->
<div id="my-popover" popover="auto">
  <p>Popover content here</p>
</div>
```

### With Anchor Positioning

```css
#menu-btn {
  anchor-name: --menu-anchor;
}

#my-popover {
  position: absolute;
  position-anchor: --menu-anchor;
  top: anchor(bottom);
  left: anchor(left);
  translate: 0 8px;
}
```

### JavaScript Control

```javascript
// Show popover
element.showPopover();

// Hide popover
element.hidePopover();

// Toggle popover
element.togglePopover();

// Check if open
element.matches(':popover-open');
```

## 🎨 Customization

### CSS Variables

The demo uses CSS custom properties for easy theming:

```css
:root {
  --color-bg-primary: #0f1724;
  --color-accent: #6ee7b7;
  --border-radius-md: 8px;
  --transition-base: 0.18s ease;
  /* ... more variables */
}
```

### Animation Timing

Adjust animation duration in the CSS:

```css
[popover] {
  transition: opacity 0.18s ease, 
              transform 0.18s ease;
}
```

## 🌐 Browser Support

| Feature | Chrome | Edge | Safari | Firefox |
|---------|--------|------|--------|---------|
| **Popover API** | 114+ | 114+ | 17+ | ❌ (fallback) |
| **Anchor Positioning** | 125+ | 125+ | ❌ | ❌ |

The demo includes JavaScript fallbacks for unsupported browsers, ensuring functionality across all modern browsers.

## ⌨️ Keyboard Shortcuts

- **Tab** - Navigate between interactive elements
- **Esc** - Close the currently open popover
- **Enter/Space** - Activate buttons and links
- **Arrow Keys** - Navigate within menu items

## 🤝 Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct.

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [MDN Web Docs](https://developer.mozilla.org/) - Popover API documentation
- [CSS-Tricks](https://css-tricks.com/) - Popover and anchor positioning articles
- [WHATWG](https://html.spec.whatwg.org/multipage/popover.html) - HTML Popover specification
- [Open UI](https://open-ui.org/) - Popover research and design patterns

## 📚 Resources

- [Popover API - MDN](https://developer.mozilla.org/en-US/docs/Web/API/Popover_API)
- [CSS Anchor Positioning - Chrome Developers](https://developer.chrome.com/blog/anchor-positioning-api/)
- [ARIA Authoring Practices Guide](https://www.w3.org/WAI/ARIA/apg/)

## 👤 Author

**Your Name**
- GitHub: [@your-username](https://github.com/your-username)
- Twitter: [@your-twitter](https://twitter.com/your-twitter)

## 🌟 Show Your Support

Give a ⭐️ if this project helped you!

---

Made with ❤️ and modern web standards
