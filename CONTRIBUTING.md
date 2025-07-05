# Contributing to Netflix Household Unblocker

Thank you for your interest in contributing to Netflix Household Unblocker! This document provides guidelines and information for contributors.

## 🚀 Getting Started

### Prerequisites
- Basic knowledge of JavaScript and browser extension development
- Familiarity with Chrome Extension Manifest V3
- Understanding of DOM manipulation and network request handling

### Development Setup
1. Clone the repository
2. Load the extension in your browser for testing
3. Make your changes
4. Test thoroughly on Netflix
5. Submit a pull request

## 📝 Code Style Guidelines

### JavaScript
- Use ES6+ features where appropriate
- Follow consistent naming conventions
- Add meaningful comments for complex logic
- Keep functions focused and single-purpose

### HTML/CSS
- Use semantic HTML elements
- Follow BEM methodology for CSS classes
- Ensure responsive design principles
- Maintain accessibility standards

## 🧪 Testing

### Manual Testing Checklist
- [ ] Extension loads without errors
- [ ] Toggle functionality works correctly
- [ ] Network request blocking functions on `/watch` pages
- [ ] Modal hiding works on browse pages
- [ ] No console errors in normal operation
- [ ] Extension doesn't interfere with normal Netflix functionality

### Testing Environments
- Chrome (latest version)
- Firefox (latest version)
- Edge (latest version)
- Brave (latest version)

## 🐛 Bug Reports

When reporting bugs, please include:
- Browser and version
- Extension version
- Steps to reproduce
- Expected vs actual behavior
- Console errors (if any)
- Screenshots (if applicable)

## 💡 Feature Requests

For feature requests, please:
- Describe the feature clearly
- Explain the use case
- Consider implementation complexity
- Check if it aligns with project goals

## 📋 Pull Request Guidelines

1. **Fork the repository**
2. **Create a feature branch**: `git checkout -b feature/amazing-feature`
3. **Make your changes**: Follow the coding guidelines
4. **Test thoroughly**: Ensure all functionality works
5. **Commit your changes**: Use clear, descriptive commit messages
6. **Push to the branch**: `git push origin feature/amazing-feature`
7. **Open a Pull Request**: Provide clear description of changes

### Commit Message Format
```
type(scope): description

Examples:
feat(background): add new network request filtering
fix(content): resolve modal hiding edge case
docs(readme): update installation instructions
```

## 🔒 Security Considerations

- Never include API keys or sensitive data
- Follow security best practices
- Report security vulnerabilities privately
- Test changes thoroughly before submission

## 📄 License

By contributing to this project, you agree that your contributions will be licensed under the MIT License.

## 🤝 Questions?

If you have questions about contributing, please:
1. Check existing issues and discussions
2. Create a new issue for general questions
3. Be respectful and constructive in all interactions

Thank you for contributing to Netflix Household Unblocker! 🎉 