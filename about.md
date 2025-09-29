---
layout: page
title: About
permalink: /about/
---

# About This Jekyll Test Site

This is a demonstration site for testing Jekyll with GitHub Actions automation.

## Purpose

This repository serves as a test environment for:

- **Jekyll Site Development**: Building static sites with Jekyll
- **GitHub Actions CI/CD**: Automating deployment with GitHub Actions
- **Content Management**: Managing blog posts and pages with Markdown
- **Theme Integration**: Using Jekyll themes like Minima

## Technology Stack

- **Jekyll**: Static site generator
- **GitHub Actions**: CI/CD pipeline
- **GitHub Pages**: Hosting platform
- **Minima Theme**: Default Jekyll theme
- **Markdown**: Content writing format

## Repository Structure

```
jekylltest/
├── _config.yml          # Jekyll configuration
├── _posts/              # Blog posts
├── _layouts/            # Page layouts
├── _includes/           # Reusable components
├── .github/workflows/   # GitHub Actions workflows
├── Gemfile             # Ruby dependencies
├── index.md            # Homepage
└── about.md            # This page
```

## GitHub Actions Workflow

The site is automatically built and deployed using GitHub Actions whenever changes are pushed to the main branch. The workflow:

1. Checks out the code
2. Sets up Ruby and Jekyll
3. Builds the site
4. Deploys to GitHub Pages

This provides a seamless development experience with automatic deployments.