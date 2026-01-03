# Contributing to Sudoku PWA

Thank you for your interest in contributing to the Sudoku Progressive Web App! This document provides guidelines and instructions for contributing.

## Code of Conduct

- Be respectful and inclusive
- Welcome all contributors regardless of experience level
- Focus on constructive feedback
- Respect differing opinions

## How to Contribute

### Reporting Bugs

Found a bug? Please create an issue with:

1. **Clear title** - Briefly describe the bug
2. **Detailed description** - What happened and what should have happened
3. **Steps to reproduce** - How to recreate the issue
4. **Device info** - iPhone/Android, browser, OS version
5. **Screenshots** - If applicable
6. **Error messages** - Any console errors (press F12 to open developer tools)

### Suggesting Features

Have an idea? Open an issue with:

1. **Clear title** - What feature would you like?
2. **Description** - Why would this be useful?
3. **Example usage** - How would users interact with it?
4. **Mockup or wireframe** - Visual representation (optional)

### Submitting Code Changes

1. **Fork the repository**
   - Click "Fork" on GitHub

2. **Create a branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

3. **Make your changes**
   - Keep changes focused and minimal
   - Follow the existing code style
   - Add comments for complex logic

4. **Test your changes**
   - Test on both desktop and mobile
   - Test offline functionality
   - Check performance
   - Verify no console errors

5. **Commit your changes**
   ```bash
   git commit -m "Brief description of changes"
   ```

6. **Push to your fork**
   ```bash
   git push origin feature/your-feature-name
   ```

7. **Submit a Pull Request**
   - Go to the original repository
   - Click "New Pull Request"
   - Select your branch
   - Describe your changes
   - Wait for review

## Development Setup

### Requirements
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Text editor (VS Code recommended)
- Git
- GitHub account

### Local Setup
1. Clone the repository
   ```bash
   git clone https://github.com/YOUR-USERNAME/sudoku-pwa.git
   cd sudoku-pwa
   ```

2. Open in browser
   ```bash
   # Option 1: Double-click index.html
   # Option 2: Use a local server
   python -m http.server 8000
   # Then visit http://localhost:8000
   ```

3. Open developer tools (F12) to check console

## Code Style

### HTML
- Use semantic HTML elements
- Proper indentation (2 spaces)
- Descriptive IDs and classes
- Accessible form labels

### CSS
- Follow existing variable naming (--color-*, --space-*, etc.)
- Use CSS variables for colors
- Mobile-first approach
- Test at multiple viewport sizes

### JavaScript
- Use ES6+ syntax (const/let, arrow functions)
- Descriptive variable names
- Add comments for complex logic
- Avoid console.log in production
- Handle errors gracefully

## Project Structure

```
sudoku-pwa/
├── index.html          # Main game file
├── manifest.json       # PWA metadata
├── sw.js              # Service worker
├── README.md          # Documentation
├── LICENSE            # MIT License
├── CONTRIBUTING.md    # This file
└── .gitignore         # Git ignore rules
```

## Testing Checklist

Before submitting a PR, test:

- [ ] Desktop browser (Chrome, Firefox, Safari, Edge)
- [ ] Mobile browser (Chrome on Android, Safari on iOS)
- [ ] Offline functionality
- [ ] Install as PWA works
- [ ] No console errors (F12)
- [ ] Responsive design at different viewport sizes
- [ ] All buttons and features work
- [ ] Performance is acceptable
- [ ] Statistics save/persist

## Performance Guidelines

Keep the game performant:
- Minimize file sizes
- Avoid unnecessary DOM manipulation
- Cache efficiently
- Test on slower devices/networks
- Monitor bundle size

## Documentation

- Update README.md for major changes
- Add comments for complex algorithms
- Document new features
- Include examples where helpful

## Getting Help

- Check existing issues first
- Ask in GitHub Discussions
- Review similar contributions
- Don't hesitate to ask questions

## Recognition

All contributors will be:
- Listed in the README.md
- Recognized in commit messages
- Thanked for their work

## License

By contributing, you agree that your contributions will be licensed under the MIT License.

## Questions?

Open an issue with the "question" label and we'll help!

---

**Thank you for contributing to make Sudoku PWA better!** 🎮✨