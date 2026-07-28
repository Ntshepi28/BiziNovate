# BiziNovate ICT Academy
## Team Development Guide

---

## Project Information

**Project:** BiziNovate ICT Academy Website

**Development Team:** 2 Developers

**Frontend Stack**

- HTML5
- CSS3
- JavaScript (ES6)
- Git & GitHub
- Netlify

---

# Project Goal

Develop a professional, responsive, and accessible website for BiziNovate ICT Academy that showcases its programmes, impact, partnerships, and provides a foundation for future student and administrator portals.

---

# Team Roles

## Developer 1

Responsible for:

- HTML Structure
- Accessibility
- Website Content
- SEO
- Documentation

---

## Developer 2

Responsible for:

- CSS Styling
- Responsive Design
- JavaScript
- User Experience
- Testing

---

# Branch Strategy

Never work directly on `main`.

```
main
│
develop
│
├── feature/homepage
├── feature/about-page
├── feature/programmes-page
├── feature/contact-page
├── feature/student-dashboard
└── feature/certificates
```

---

# Git Workflow

1. Pull latest changes
2. Create a feature branch
3. Build the feature
4. Commit changes
5. Push branch
6. Open Pull Request
7. Code Review
8. Merge into develop
9. Test
10. Merge develop into main

---

# Commit Message Convention

Use meaningful commits.

Examples:

```
feat(home): create hero section

feat(navbar): add responsive navigation

fix(footer): correct social links

docs: update README

style(home): improve spacing

refactor(navbar): simplify structure
```

Avoid:

```
update

changes

fixed

done

work
```

---

# HTML Standards

Use semantic HTML.

Preferred elements:

- header
- nav
- main
- section
- article
- aside
- footer

Every page must have:

- One H1
- Proper heading hierarchy
- Meaningful alt text
- Comments for major sections

---

# CSS Standards

Follow BEM naming.

Example:

```
navbar

navbar__logo

navbar__links

navbar__item

navbar__link

btn

btn-primary
```

Avoid IDs for styling.

Use classes.

---

# JavaScript Standards

Use:

- const
- let
- Arrow functions
- Template literals
- Async/Await

Avoid:

- var
- Inline JavaScript
- Global variables

---

# Folder Structure

```
src/

assets/

components/

data/

docs/
```

Keep folders organised.

---

# Naming Convention

Files

```
about.html

contact.html

style.css

include.js
```

Images

```
hero-image.jpg

founder-photo.jpg

student-1.jpg
```

---

# Accessibility

Every image

Must include alt text.

Buttons

Must have descriptive labels.

Navigation

Must support keyboard navigation.

Forms

Must include labels.

---

# Browser Support

Test on:

- Chrome
- Firefox
- Edge

---

# Responsive Design

Support:

Desktop

Tablet

Mobile

---

# Code Review Checklist

Before merging:

✓ HTML validates

✓ No console errors

✓ Responsive

✓ Links work

✓ Images load

✓ Components reused

✓ No duplicated code

✓ Accessibility checked

---

# Deployment

Hosting:

Netlify

Production Branch:

main

---

# Future Roadmap

Phase 1

- Public Website

Phase 2

- Student Portal

Phase 3

- Admin Dashboard

Phase 4

- Certificate Verification

Phase 5

- Online Learning Platform

---

# Team Communication

Before starting a task:

- Check GitHub Issues
- Pull latest changes
- Create feature branch

After completing a task:

- Test locally
- Commit changes
- Push branch
- Open Pull Request

---

# Definition of Done

A task is complete when:

✓ Feature works

✓ Code reviewed

✓ Tested

✓ Responsive

✓ Accessible

✓ Merged into develop

✓ Documentation updated if needed

---

End of Document