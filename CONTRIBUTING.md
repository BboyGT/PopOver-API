# Contributing to Popover API Demo

First off, thank you for considering contributing to this project! 🎉

## Code of Conduct

This project and everyone participating in it is governed by our commitment to providing a welcoming and inspiring community for all. Please be respectful and constructive in your interactions.

## How Can I Contribute?

### Reporting Bugs

Before creating bug reports, please check the existing issues to avoid duplicates. When you create a bug report, include as many details as possible:

- **Use a clear and descriptive title**
- **Describe the exact steps to reproduce the problem**
- **Provide specific examples to demonstrate the steps**
- **Describe the behavior you observed and what you expected**
- **Include screenshots if applicable**
- **Note your browser and OS version**

### Suggesting Enhancements

Enhancement suggestions are tracked as GitHub issues. When creating an enhancement suggestion, include:

- **Use a clear and descriptive title**
- **Provide a detailed description of the suggested enhancement**
- **Explain why this enhancement would be useful**
- **List any examples of how other projects implement this feature**

### Pull Requests

1. **Fork the repo** and create your branch from `main`
2. **Make your changes** - ensure code follows the existing style
3. **Test your changes** across different browsers if possible
4. **Update documentation** if you've changed functionality
5. **Write clear commit messages** following the format below
6. **Submit a pull request** with a comprehensive description

## Development Process

### Setting Up Your Development Environment

```bash
# Clone your fork
git clone https://github.com/your-username/popover-api-demo.git
cd popover-api-demo

# Create a branch
git checkout -b feature/my-new-feature

# Make your changes and test locally
# Open index.html in your browser

# Commit your changes
git add .
git commit -m "Add new feature: description"

# Push to your fork
git push origin feature/my-new-feature
```

### Commit Message Guidelines

Use clear and meaningful commit messages:

```
feat: Add new popover variant for modal dialogs
fix: Correct anchor positioning on mobile devices
docs: Update README with new examples
style: Format CSS with consistent indentation
refactor: Simplify popover initialization logic
test: Add keyboard navigation tests
```

### Code Style Guidelines

#### HTML
- Use semantic HTML5 elements
- Include ARIA attributes for accessibility
- Use meaningful IDs and class names
- Maintain proper indentation (2 spaces)

#### CSS
- Use CSS custom properties for theming
- Follow BEM-like naming convention for classes
- Group related properties together
- Add comments for complex sections
- Maintain consistent spacing

#### JavaScript
- Use modern ES6+ syntax
- Write clear, self-documenting code
- Add comments for complex logic
- Handle errors gracefully
- Maintain consistent formatting

### Testing

Before submitting a pull request, please test:

- ✅ All popover variants work correctly
- ✅ Keyboard navigation (Tab, Esc, Enter)
- ✅ Screen reader compatibility
- ✅ Mobile responsiveness
- ✅ Browser compatibility (Chrome, Firefox, Safari, Edge)
- ✅ Fallback behavior for unsupported features

### Documentation

If you're adding new features:

- Update the README.md with usage examples
- Add inline code comments
- Update the demo if applicable
- Document any new CSS variables or options

## Project Structure

```
popover-api-demo/
├── index.html          # Main HTML file with embedded CSS/JS
├── README.md           # Project documentation
├── LICENSE             # MIT License
├── CONTRIBUTING.md     # This file
└── .gitignore         # Git ignore rules
```

## Questions?

Feel free to open an issue with the `question` label if you have any questions about contributing.

## Recognition

Contributors will be recognized in the project README. Thank you for your contributions! 🙏

---

**Happy Contributing!** 🚀