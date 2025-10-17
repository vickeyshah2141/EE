# 🤝 Contributing to EaglEye

Thank you for your interest in contributing to EaglEye! This document provides guidelines and information for contributors.

## 🌟 Welcome Contributors!

We believe that great projects are built by great communities. Whether you're a cybersecurity expert, a web developer, a designer, or just someone who wants to help, there's a place for you here!

## 🎯 Ways to Contribute

### 🐛 Bug Reports
- Check existing [issues](../../issues) first to avoid duplicates
- Use the bug report template when available
- Include detailed steps to reproduce the issue
- Add screenshots or error messages if applicable
- Specify browser and operating system details

### 💡 Feature Requests
- Describe the feature clearly and its use case
- Explain why this feature would benefit the project
- Consider the scope and complexity of the implementation
- Be open to discussion and alternative approaches

### 🔧 Code Contributions
- **Frontend Improvements**: Enhance UI/UX, responsiveness, accessibility
- **Data Visualization**: Improve charts, maps, and statistical displays
- **Performance**: Optimize loading times and data processing
- **Browser Compatibility**: Ensure cross-browser functionality
- **Mobile Support**: Improve mobile device experience

### 📚 Documentation
- Improve README clarity and completeness
- Add code comments and documentation
- Create tutorials or guides
- Fix typos and grammar errors
- Translate documentation to other languages

### 🎨 Design & Assets
- Improve visual design and user interface
- Create new icons or graphics
- Enhance color schemes and layouts
- Design logos or promotional materials
- Optimize images for web performance

### 🔍 Security & Data Analysis
- Review security implementations
- Validate threat intelligence data
- Improve malware analysis accuracy
- Add new data sources or analysis methods
- Enhance data visualization techniques

## 🚀 Getting Started

### 1. Fork and Clone
```bash
# Fork the repository on GitHub first, then:
git clone https://github.com/YOUR-USERNAME/EE.git
cd EE
```

### 2. Set Up Development Environment
```bash
# Start a local web server (choose one method):

# Python 3
python -m http.server 8000

# Node.js
npx http-server

# PHP
php -S localhost:8000
```

### 3. Create a Branch
```bash
git checkout -b feature/your-feature-name
# or
git checkout -b fix/your-bug-fix
```

### 4. Make Your Changes
- Follow the coding standards below
- Test your changes thoroughly
- Update documentation if needed

### 5. Commit Your Changes
```bash
git add .
git commit -m "feat: add new threat visualization feature"
# or
git commit -m "fix: resolve map loading issue in Firefox"
```

### 6. Push and Create Pull Request
```bash
git push origin your-branch-name
```
Then create a Pull Request on GitHub.

## 📋 Coding Standards

### HTML
- Use semantic HTML5 elements
- Maintain proper indentation (2 spaces)
- Include appropriate meta tags and accessibility attributes
- Validate HTML using W3C validator

### CSS
- Follow BEM methodology for class naming
- Use consistent indentation (2 spaces)
- Organize CSS properties logically
- Use CSS variables for colors and common values
- Ensure responsive design principles

### JavaScript
- Use ES6+ features when appropriate
- Follow consistent naming conventions (camelCase)
- Add comments for complex logic
- Handle errors gracefully
- Optimize for performance and readability

### JSON Data Files
- Validate JSON syntax
- Use consistent formatting and indentation
- Document data structure and field meanings
- Ensure data accuracy and attribution

## 🎃 Hacktoberfest Guidelines

### Eligible Contributions
- ✅ Bug fixes with clear documentation
- ✅ New features that enhance functionality
- ✅ UI/UX improvements
- ✅ Documentation improvements
- ✅ Performance optimizations
- ✅ Accessibility enhancements

### Non-Eligible Contributions
- ❌ Spam or low-quality submissions
- ❌ Automated or scripted changes without value
- ❌ Duplicate issues or pull requests
- ❌ Changes that break existing functionality
- ❌ Trivial changes (fixing typos in comments)

### Quality Standards
- Make meaningful contributions
- Test your changes thoroughly
- Follow the project's coding standards
- Write clear commit messages
- Be responsive to feedback during review

## 🧪 Testing Guidelines

### Before Submitting
- [ ] Test in multiple browsers (Chrome, Firefox, Safari, Edge)
- [ ] Verify mobile responsiveness
- [ ] Check console for JavaScript errors
- [ ] Validate HTML and CSS
- [ ] Test with different data sets if applicable
- [ ] Ensure all links and resources load correctly

### Cross-Browser Testing
- Desktop: Latest versions of Chrome, Firefox, Safari, Edge
- Mobile: iOS Safari, Chrome Mobile, Samsung Internet
- Report any browser-specific issues

## 📝 Pull Request Guidelines

### PR Title Format
- `feat: add new feature description`
- `fix: resolve specific issue`
- `docs: update documentation`
- `style: improve UI/UX elements`
- `perf: optimize performance`
- `refactor: improve code structure`

### PR Description Template
```markdown
## Description
Brief description of changes made

## Type of Change
- [ ] Bug fix
- [ ] New feature
- [ ] Documentation update
- [ ] Performance improvement
- [ ] UI/UX enhancement

## Testing
- [ ] Tested in multiple browsers
- [ ] Mobile responsive
- [ ] No console errors
- [ ] Functionality verified

## Screenshots (if applicable)
Add screenshots for UI changes

## Additional Notes
Any additional context or considerations
```

### Review Process
1. Automated checks (if any) must pass
2. Code review by maintainers
3. Testing verification
4. Approval and merge

## 🏷️ Issue Labels

- `good first issue`: Perfect for newcomers
- `hacktoberfest`: Hacktoberfest-eligible issues
- `bug`: Something isn't working
- `enhancement`: New feature or improvement
- `documentation`: Documentation needs
- `help wanted`: Extra attention needed
- `question`: Further information requested
- `wontfix`: Will not be worked on

## 🆘 Getting Help

### Stuck? Need Assistance?
- 💬 Comment on relevant issues
- 📧 Create a new issue with the `question` label
- 🔍 Check existing documentation and issues first
- 📖 Review the README for setup instructions

### Community Guidelines
- Be respectful and inclusive
- Help others when you can
- Ask questions - no question is too basic
- Share knowledge and learn from others
- Follow our [Code of Conduct](CODE_OF_CONDUCT.md)

## 🎖️ Recognition

### Contributors
All contributors will be recognized in:
- Project documentation
- Release notes for significant contributions
- Special mention for outstanding contributions

### Maintainers
Current maintainers who review and manage contributions:
- Andrea Cristaldi (Original Author)
- Community volunteers

## 📋 Development Workflow

### Issue Lifecycle
1. **Open**: Issue created and awaiting triage
2. **Assigned**: Issue assigned to contributor
3. **In Progress**: Work has begun
4. **Review**: Pull request submitted
5. **Merged**: Changes accepted and merged
6. **Closed**: Issue resolved

### Release Process
- Regular updates and improvements
- Version tagging for major releases
- Changelog maintenance
- Community announcements

## 📄 Legal

By contributing to EaglEye, you agree that your contributions will be licensed under the same license as the project (MIT License).

---

**Thank you for contributing to EaglEye! Together, we're building a better threat intelligence platform for the cybersecurity community.** 🦅✨