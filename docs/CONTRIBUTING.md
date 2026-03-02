# Contributing to HTML Course

Thank you for your interest in contributing to this HTML learning repository! This guide explains how you can help improve the project.

## Ways to Contribute

### 1. Report Issues
- Found an error in the code?
- Typo in documentation?
- File doesn't display correctly?

**How to report:**
- Open a GitHub Issue
- Describe the problem clearly
- Include which file(s) are affected
- Specify your browser and OS

### 2. Improve Documentation
- Enhance README files
- Add explanations to learning guides
- Create new tutorials or guides
- Fix typos or unclear wording

**How to contribute:**
- Fork the repository
- Create a new branch: `git checkout -b docs/your-enhancement`
- Make your changes
- Submit a pull request

### 3. Add Examples
- Create new HTML files demonstrating concepts
- Add comments explaining the code
- Follow the existing naming conventions
- Test thoroughly before submitting

**File Naming Guidelines:**
- Use descriptive names: `topic-name.html`
- Use lowercase with hyphens
- Keep it concise but clear
- Examples: `css-navbar.html`, `form-validation.html`

### 4. Enhance Existing Files
- Add more explanatory comments
- Improve styling
- Make examples clearer
- Add more realistic content

### 5. Create New Topics
- HTML5 semantic elements
- Forms and input validation
- Accessibility (a11y) examples
- Responsive design patterns
- SEO best practices

## Development Workflow

### 1. Fork the Repository
```bash
# Click "Fork" on GitHub
```

### 2. Clone Your Fork
```bash
git clone https://github.com/YOUR-USERNAME/HTML_Course.git
cd HTML_Course
```

### 3. Create a Topic Branch
```bash
git checkout -b feature/description-of-feature
# or
git checkout -b docs/description-of-documentation
# or
git checkout -b fix/description-of-bug
```

### 4. Make Your Changes
- Edit files as needed
- Test thoroughly
- Add comments and documentation
- Follow coding standards (see below)

### 5. Commit Your Changes
```bash
git add .
git commit -m "Brief description of changes"
# Good example: "Add form validation example"
# Bad example: "fixed stuff"
```

### 6. Push to Your Fork
```bash
git push origin feature/your-feature-name
```

### 7. Create a Pull Request
- Go to GitHub
- Click "New Pull Request"
- Select your branch
- Describe your changes
- Submit!

## Coding Standards

### HTML
- Use proper indentation (2 spaces)
- Always include DOCTYPE
- Use semantic HTML5 tags when appropriate
- Add comments for complex sections
- Validate with https://validator.w3.org/

### File Structure
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Page Title</title>
    <style>
        /* CSS here */
    </style>
</head>
<body>
    <!-- Content here -->
    <script>
        // JavaScript here (if needed)
    </script>
</body>
</html>
```

### Comments
```html
<!-- Main section -->
<section>
    <!-- Subsection with explanation -->
    <article>Content</article>
</section>
```

### CSS
- Use meaningful class names
- Keep selectors simple
- Avoid inline styles when possible
- Comment complex rules

### File Organization
- Place related files together
- Use consistent naming conventions
- Create subdirectories for new topics
- Update documentation when adding files

## Documentation Standards

### File Headers
Include a comment at the top of each file:
```html
<!--
Title: What this file demonstrates
Topics: Related concepts or tags
Level: Beginner / Intermediate / Advanced
Description: Brief explanation of content
-->
```

### Code Comments
- Comment the "why" not the "what"
- Explain non-obvious techniques
- Keep comments concise

### README Sections
When adding new content:
- Add to appropriate topic section
- Include file name and description
- Add to learning path if applicable
- Update table of contents

## Testing Your Changes

Before submitting:

1. **Open in Multiple Browsers**
   - Chrome
   - Firefox
   - Safari
   - Edge

2. **Validate HTML**
   - https://validator.w3.org/
   - Fix any errors or warnings

3. **Check Responsive Design**
   - Desktop: 1920x1080
   - Tablet: 768x1024
   - Mobile: 375x667

4. **Verify Documentation**
   - Check for typos
   - Ensure links work
   - Verify file references are correct

## Pull Request Guidelines

Your PR should:
- Address a single feature or issue
- Have clear commit messages
- Include updated documentation
- Pass all validation checks
- Follow our code standards

### PR Title Format
- `[docs]` - Documentation changes
- `[feature]` - New example or feature
- `[fix]` - Bug fixes or corrections
- `[enhance]` - Improvements to existing content

Example: `[feature] Add HTML5 semantic elements guide`

## Commit Message Guidelines

Good commit messages:
- Start with present tense verb: "Add", "Fix", "Update"
- Be specific about what changed: "Add color picker example"
- Keep it short (50 characters or less)
- Reference issues if applicable: "Fixes #123"

Examples:
- ✅ `Add image optimization guide`
- ✅ `Fix typo in table borders example`
- ✅ `Update color chart with accessibility info`
- ❌ `update stuff`
- ❌ `fixed`

## Code Review Process

1. Maintainers will review your PR
2. You may receive feedback or requests for changes
3. Make requested changes and push updated commits
4. Once approved, your PR will be merged

## Questions?

- Open an issue for questions
- Check existing issues for similar questions
- Review existing code for examples
- Comment on PRs for clarification

## Recognition

Contributors will be:
- Listed in the repository
- Credited in commit history
- Thanked in documentation

## Code of Conduct

- Be respectful and inclusive
- Provide constructive feedback
- No harassment or discrimination
- Focus on the work, not the person

## License

By contributing, you agree that your contributions will be licensed under the same license as the project.

---

## Quick Checklist for Contributors

- [ ] Fork and clone the repository
- [ ] Create a descriptive branch name
- [ ] Make your changes
- [ ] Test in multiple browsers
- [ ] Validate HTML
- [ ] Update documentation
- [ ] Commit with clear messages
- [ ] Push to your fork
- [ ] Create a pull request
- [ ] Respond to feedback
- [ ] Celebrate! 🎉

---

Thank you for helping make this learning resource better!
