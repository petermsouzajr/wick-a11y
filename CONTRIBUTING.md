# Contributing to wick-a11y

Thank you for your interest in contributing to wick-a11y! We welcome contributions from the community and are grateful for your help in making accessibility testing more accessible to everyone.

## 🤝 How to Contribute

### Types of Contributions

We welcome several types of contributions:

- **🐛 Bug Reports**: Help us identify and fix issues
- **✨ Feature Requests**: Suggest new functionality
- **📝 Documentation**: Improve our docs, examples, and guides
- **🔧 Code Contributions**: Fix bugs, implement features, or improve existing code
- **🧪 Testing**: Help us test new features and ensure quality
- **💡 Ideas**: Share your thoughts on improving the project

## 🚀 Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn
- Git
- Basic knowledge of Cypress and accessibility testing

### Development Setup

1. **Fork the repository** on GitHub
2. **Clone your fork** locally:
   ```bash
   git clone https://github.com/YOUR_USERNAME/wick-a11y.git
   cd wick-a11y
   ```

3. **Install dependencies**:
   ```bash
   npm install
   ```

4. **Create a new branch** for your changes:
   ```bash
   git checkout -b feature/your-feature-name
   # or
   git checkout -b fix/your-bug-fix
   ```

5. **Make your changes** and test them thoroughly

6. **Run tests** to ensure everything works:
   ```bash
   npm run cy:run
   ```

## 📝 Code Contribution Guidelines

### Code Style

- Follow the existing code style and patterns
- Use meaningful variable and function names
- Add comments for complex logic
- Ensure all new code is properly documented

### Testing

- **Always test your changes** before submitting
- Add tests for new features when applicable
- Ensure existing tests still pass
- Test with different Cypress versions when possible

### Commit Messages

Use clear, descriptive commit messages:

```bash
# Good examples
feat: add voice support for DOM element violations
fix: resolve screenshot path issues for nested tests
docs: update API documentation for new options
test: add tests for custom impact styling

# Avoid
fix stuff
update
changes
```

### Pull Request Process

1. **Ensure your branch is up to date** with the main branch:
   ```bash
   git checkout main
   git pull origin main
   git checkout your-branch
   git rebase main
   ```

2. **Test your changes thoroughly**:
   - Run the test suite
   - Test with different configurations
   - Verify accessibility reports are generated correctly

3. **Create a pull request** with:
   - Clear title describing the change
   - Detailed description of what was changed and why
   - Reference any related issues
   - Screenshots or examples if applicable

4. **Respond to feedback** promptly and make requested changes

## 🐛 Bug Reports

When reporting bugs, please include:

- **Clear description** of the issue
- **Steps to reproduce** the problem
- **Expected behavior** vs actual behavior
- **Environment details**:
  - Cypress version
  - Node.js version
  - Operating system
  - Browser version
- **Code examples** that demonstrate the issue
- **Screenshots or error messages** if applicable

Use our [bug report template](.github/ISSUE_TEMPLATE/bug_report.md) when creating issues.

## ✨ Feature Requests

When suggesting new features:

- **Describe the problem** you're trying to solve
- **Explain your proposed solution**
- **Provide use cases** and examples
- **Consider alternatives** you've explored
- **Check existing issues** to avoid duplicates

Use our [feature request template](.github/ISSUE_TEMPLATE/feature_request.md) when creating issues.

## 📚 Documentation Contributions

We welcome documentation improvements:

- **Fix typos** and grammatical errors
- **Improve clarity** of existing documentation
- **Add examples** and use cases
- **Update outdated information**
- **Translate documentation** to other languages

### Documentation Guidelines

- Use clear, concise language
- Include code examples where helpful
- Follow the existing documentation style
- Test all code examples before submitting

## 🧪 Testing Contributions

Help us maintain quality by:

- **Testing new features** in different environments
- **Reporting edge cases** and unexpected behavior
- **Suggesting test improvements**
- **Testing with different accessibility tools**

## 🏗️ Project Structure

Understanding the project structure will help you contribute effectively:

```
wick-a11y/
├── src/                          # Source code
│   ├── accessibility-commands.js # Main Cypress command
│   ├── accessibility-log.js      # Logging and violation handling
│   ├── accessibility-report.js   # HTML report generation
│   ├── accessibility-tasks.js    # Cypress tasks
│   ├── accessibility-voice.js    # Voice support functionality
│   ├── index.js                  # Main entry point
│   └── index.d.ts                # TypeScript definitions
├── cypress/                      # Test files and examples
├── images/                       # Documentation images
└── docs/                         # Additional documentation
```

## 🎯 Development Focus Areas

We're particularly interested in contributions that:

- **Improve accessibility** of the plugin itself
- **Enhance voice support** functionality
- **Optimize performance** for large applications
- **Add new reporting formats** (JSON, XML, etc.)
- **Improve error handling** and user experience
- **Add support for new accessibility standards**

## 💬 Community Guidelines

### Be Respectful

- Use welcoming and inclusive language
- Be respectful of differing viewpoints and experiences
- Accept constructive criticism gracefully
- Focus on what's best for the community

### Be Collaborative

- Help others when you can
- Share knowledge and resources
- Work together to solve problems
- Give credit where credit is due

### Be Professional

- Keep discussions focused on the project
- Avoid personal attacks or inflammatory language
- Follow the project's code of conduct
- Remember that this is a public project

## 🚫 What Not to Contribute

Please avoid:

- **Breaking changes** without discussion
- **Code without tests** (when applicable)
- **Large refactoring** without prior discussion
- **Dependencies** that significantly increase bundle size
- **Features** that are too specific to one use case

## 📞 Getting Help

If you need help:

- **Check existing issues** and discussions
- **Read the documentation** thoroughly
- **Join our community discussions** (if available)
- **Create a question issue** with the "question" label

## 📋 Checklist for Contributors

Before submitting your contribution:

- [ ] I have read and understood the contributing guidelines
- [ ] I have tested my changes thoroughly
- [ ] I have updated documentation if needed
- [ ] I have added tests for new functionality
- [ ] My code follows the project's style guidelines
- [ ] I have created a clear, descriptive pull request
- [ ] I have referenced any related issues

## 🎉 Thank You!

Your contributions help make wick-a11y better for everyone in the accessibility community. We appreciate your time and effort in helping us create more inclusive web applications.

---

**Questions?** Feel free to open an issue with the "question" label, and we'll be happy to help!
