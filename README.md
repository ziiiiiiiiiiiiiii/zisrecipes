# zisrecipes
A simple HTML/CSS website of my authentic home-style Chinese recipes from my mother's kitchen. These are some of the staple dishes I grew up on. Includes an index page with recipe cards that link to all the recipes on separate pages. This project is also used to practice Git workflows, feature branches, pull requests, and GitHub Actions CI.

Feature Branch: ingredient-checkboxes
- Adds checkboxes to ingredient lists for better usability
  
Feature Branch: dark-mode
- Adds toggle dark mode button across all pages of the site

Feature Branch: heading-colour
- Adjusts colour of heading text

Other features
- Homepage with clickable recipe cards
- Individual recipe pages (HTML)
- Responsive layout
- Dark mode toggle with localStorage
- Organized folder structure (`recipes/`, `images/`, `styles.css`)
- Automated HTML & CSS validation using GitHub Actions

Continuous Integration (GitHub Actions)

This project includes a workflow that validates:

- **HTML** using `html5validator`
- **CSS** using the official W3C CSS Validator API

The workflow runs automatically on:

- every push  
- every pull request  

You can find it in: .github/workflows/main.yml
