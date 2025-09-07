---
name: Bug Report
about: Create a report to help us improve wick-a11y
title: '[BUG] '
labels: ['bug', 'needs-triage']
assignees: ''
---

## ❌ Actual Behavior

A clear and concise description of what actually happened.

## ✅ Expected Behavior

A clear and concise description of what you expected to happen.

## 🔄 Steps to Reproduce

1. Go to '...'
2. Click on '....'
3. Scroll down to '....'
4. See error

## 📸 Screenshots

If applicable, add screenshots to help explain your problem.

## 🖥️ Environment

**Desktop (please complete the following information):**
- OS: [e.g. macOS, Windows, Linux]
- Browser: [e.g. Chrome, Firefox, Safari]
- Browser Version: [e.g. 22]
- Node.js Version: [e.g. 18.17.0]
- Cypress Version: [e.g. 14.0.3]
- wick-a11y Version: [e.g. 2.0.1]

## 📝 Code Example

```javascript
// Please provide a minimal code example that reproduces the issue
describe('Accessibility Test', () => {
  it('should reproduce the bug', () => {
    cy.visit('https://example.com');
    cy.checkAccessibility(/* your configuration */);
  });
});
```

## 📋 Configuration

If applicable, please share your Cypress configuration:

```javascript
// cypress.config.js
module.exports = defineConfig({
  // your configuration
});
```

## 🔍 Additional Context

Add any other context about the problem here.

## 📊 Error Messages

If there are any error messages, please include them here:

```
Error message here
```

## 🎯 Impact

- [ ] Low - Minor inconvenience
- [ ] Medium - Affects functionality but workaround exists
- [ ] High - Breaks core functionality
- [ ] Critical - Prevents plugin from working entirely

## 🔧 Possible Solution

If you have ideas on how to fix this issue, please describe them here.

---

**Thank you for reporting this bug! We'll investigate and get back to you as soon as possible.**
