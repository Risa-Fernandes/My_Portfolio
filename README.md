# HTML-CSS Basics: Build Your Professional Portfolio with Bootstrap

## Course Information
- **Course**: Deep Learning with Full Stack Deployment
- **Module**: Full Stack Basics
- **Chapter**: Basics of HTML-CSS

---

## Overview

This repository contains step-by-step code examples for building a professional portfolio website using **HTML**, **CSS**, and **Bootstrap 5**. Each part progressively builds upon the previous one, allowing you to learn at your own pace.

---

## Learning Objectives

By completing this chapter, you will learn:

| Concept | Description |
|---------|-------------|
| **HTML Anatomy** | Understanding `<head>` (metadata) vs `<body>` (content) |
| **Bootstrap Setup** | Adding Bootstrap via CDN |
| **Responsive Layouts** | Using containers and grid system |
| **Images** | Embedding and styling images with `<img>` |
| **Tables** | Structuring data with `<table>` |
| **Lists** | Creating ordered `<ol>` and unordered `<ul>` lists |
| **Bootstrap Classes** | Using utility classes like `text-center`, `p-5`, `bg-light` |
| **Bootstrap Templates** | Using and customizing pre-built templates from Start Bootstrap |
| **Dashboard Components** | Working with cards, charts, sidebars, and navigation bars |

---

## Folder Structure

```
HTML-CSS/
├── README.md                    # This file
├── assets/                      # Images and other assets
│   └── profile-placeholder.txt  # Placeholder for profile image
│
├── part-1-html-skeleton/        # Basic HTML structure
│   └── index.html
│
├── part-2-bootstrap-setup/      # Adding Bootstrap CDN
│   └── index.html
│
├── part-3-profile-image/        # Adding profile image
│   └── index.html
│
├── part-4-education-table/      # Adding education table & lists
│   └── index.html
│
├── part-5-bootstrap-styling/    # Applying Bootstrap utility classes
│   └── index.html
│
├── part-6-final-portfolio/      # Complete polished portfolio
│   ├── index.html
│   └── style.css
│
└── part-7-Introduce-Bootstrap/  # Bootstrap templates from Start Bootstrap
    ├── index.html               # SB Admin Dashboard
    ├── charts.html              # Charts page
    ├── tables.html              # DataTables page
    ├── login.html               # Login page
    ├── register.html            # Registration page
    ├── css/styles.css           # Template styles
    └── js/scripts.js            # Template scripts
```

---

## Part-by-Part Guide

### Part 1: HTML Skeleton (Simplest)
**File**: `part-1-html-skeleton/index.html`

Learn the basic structure of an HTML document:
- `<!DOCTYPE html>` declaration
- `<html>`, `<head>`, and `<body>` tags
- Meta tags and title
- Basic headings and paragraphs

**Key Concepts**:
```html
<head>  → Metadata (not visible on page)
<body>  → Content (visible on page)
```

---

### Part 2: Bootstrap Setup
**File**: `part-2-bootstrap-setup/index.html`

Add Bootstrap framework to your project:
- Bootstrap CSS CDN link
- Bootstrap JS Bundle
- Container class for layout

**Key Concepts**:
```html
<!-- Bootstrap CSS -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">

<!-- Bootstrap Container -->
<div class="container">...</div>
```

---

### Part 3: Profile Image
**File**: `part-3-profile-image/index.html`

Learn to add and style images:
- `<img>` tag with `src` and `alt` attributes
- Bootstrap image classes: `rounded-circle`, `img-fluid`
- Asset management basics

**Key Concepts**:
```html
<img src="path/to/image.jpg" alt="Description" class="rounded-circle">
```

---

### Part 4: Education Table
**File**: `part-4-education-table/index.html`

Structure data using tables and lists:
- `<table>`, `<thead>`, `<tbody>`, `<tr>`, `<th>`, `<td>`
- Bootstrap table class
- Unordered lists `<ul>` and list items `<li>`

**Key Concepts**:
```html
<table class="table">
    <thead>
        <tr><th>Column 1</th><th>Column 2</th></tr>
    </thead>
    <tbody>
        <tr><td>Data 1</td><td>Data 2</td></tr>
    </tbody>
</table>
```

---

### Part 5: Bootstrap Styling
**File**: `part-5-bootstrap-styling/index.html`

Master Bootstrap utility classes:
- **Spacing**: `m-*`, `p-*`, `mt-*`, `pb-*`
- **Background**: `bg-light`, `bg-dark`, `bg-primary`
- **Text**: `text-center`, `text-muted`, `fw-bold`
- **Tables**: `table-striped`, `table-hover`, `table-bordered`

**Key Concepts**:
```html
<div class="text-center p-5 bg-light rounded mb-4">
    Centered content with padding, light background, rounded corners, and bottom margin
</div>
```

---

### Part 6: Final Portfolio
**Files**: `part-6-final-portfolio/index.html`, `part-6-final-portfolio/style.css`

Complete professional portfolio with:
- Responsive navigation bar
- Hero section with gradient background
- About, Education, Skills, and Contact sections
- Bootstrap Icons integration
- Custom CSS for animations and hover effects
- Mobile-responsive design

---

### Part 7: Introduce Bootstrap - From Scratch to Templates
**Folder**: `part-7-Introduce-Bootstrap/`

This part introduces two approaches to working with Bootstrap:

#### Approach 1: Minimal Bootstrap Setup (Start from Scratch)

Create a simple HTML file with Bootstrap CDN to understand the basics:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First Bootstrap Page</title>
    <!-- Bootstrap CSS CDN -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">
</head>
<body>
    <div class="container mt-5">
        <h1 class="text-primary">Hello Bootstrap!</h1>
        <p class="lead">This is a minimal Bootstrap setup.</p>
        <button class="btn btn-success">Click Me</button>
    </div>

    <!-- Bootstrap JS Bundle CDN -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
```

**Key Concepts for Minimal Setup**:
- Add Bootstrap CSS in `<head>` section
- Add Bootstrap JS before closing `</body>` tag
- Use `container` class for responsive width
- Use utility classes like `mt-5`, `text-primary`, `btn btn-success`

---

#### Approach 2: Using Start Bootstrap Templates

Once comfortable with basics, use professional templates from [Start Bootstrap](https://startbootstrap.com/) to accelerate development.

**Template Used**: [SB Admin](https://startbootstrap.com/template/sb-admin)

**Files Included**:
| File | Description |
|------|-------------|
| `index.html` | Main dashboard with charts and cards |
| `charts.html` | Chart.js integration examples |
| `tables.html` | DataTables with sorting/filtering |
| `login.html` | Login form page |
| `register.html` | Registration form page |
| `404.html`, `401.html`, `500.html` | Error pages |

**Template Features**:
- Responsive sidebar navigation
- Top navigation bar with search
- Dashboard with area, bar, and pie charts
- DataTables integration for sortable tables
- Authentication pages (login, register, password reset)
- Font Awesome icons

---

### Activity: Customize the SB Admin Template

**Goal**: Modify the Start Bootstrap template to create your own admin dashboard.

#### Step 1: Explore the Template
1. Open `part-7-Introduce-Bootstrap/index.html` in your browser
2. Navigate through different pages (Dashboard, Charts, Tables)
3. Try the sidebar toggle and responsive features

#### Step 2: Make Your Changes

**Task 1 - Update Branding**:
- Open `index.html`
- Find `<a class="navbar-brand ps-3" href="index.html">Start Bootstrap</a>`
- Change "Start Bootstrap" to your name or project name

**Task 2 - Modify Dashboard Cards**:
- Locate the card sections in `index.html`
- Update the card titles and values
- Change card colors using Bootstrap classes (`bg-primary`, `bg-success`, `bg-warning`, `bg-danger`)

**Task 3 - Customize the Sidebar**:
- Find the `<nav class="sb-sidenav">` section
- Add or remove menu items
- Update icons using [Font Awesome](https://fontawesome.com/icons)

**Task 4 - Edit the Footer**:
- Find the `<footer>` section
- Replace copyright text with your information

#### Step 3: Advanced Customizations (Optional)
- Modify `css/styles.css` to change colors and fonts
- Update chart data in `assets/demo/chart-*.js` files
- Add new pages following the template structure

---

### How to Download Bootstrap Templates

1. Visit [Start Bootstrap](https://startbootstrap.com/)
2. Browse **Templates** or **Themes**
3. Choose a template (Free options available)
4. Click **Free Download**
5. Extract the ZIP file
6. Open `index.html` in your browser

**Popular Free Templates**:
| Template | Best For |
|----------|----------|
| [SB Admin](https://startbootstrap.com/template/sb-admin) | Admin dashboards |
| [Resume](https://startbootstrap.com/theme/resume) | Personal portfolios |
| [Agency](https://startbootstrap.com/theme/agency) | Business websites |
| [Landing Page](https://startbootstrap.com/template/landing-page) | Product launches |
| [Blog Post](https://startbootstrap.com/template/blog-post) | Blog articles |

---

## How to Use This Repository

### Option 1: Practice Step-by-Step
1. Start with `part-1-html-skeleton/index.html`
2. Open the file in your browser to see the result
3. Move to the next part when comfortable
4. Compare your own code with each part

### Option 2: Jump to Any Part
- Already know HTML basics? Start from `part-3`
- Want the complete portfolio? Use `part-6`

### Option 3: Use as Reference
- Copy code snippets you need
- Use the comments in code to understand concepts

---

## Activity: Build Your Own Portfolio

### Step 1: Setup
```bash
# Create your project folder
mkdir my-personal-html-website
cd my-personal-html-website

# Initialize git
git init
```

### Step 2: Create Your Portfolio
1. Copy the code from `part-6-final-portfolio`
2. Modify with your own information:
   - Replace "Your Name" with your actual name
   - Update educational details in the table
   - Add your skills
   - Update social media links

### Step 3: Add Your Profile Photo
1. Save your photo in the project folder
2. Update the `<img src="...">` path

### Step 4: Deploy to GitHub
```bash
# Add all files
git add .

# Commit
git commit -m "Initial commit: My portfolio website"

# Create repo on GitHub named 'my-personal-html-website'
# Then push
git remote add origin https://github.com/YOUR_USERNAME/my-personal-html-website.git
git push -u origin main
```

---

## Bootstrap Quick Reference

### Spacing Classes
| Class | Description |
|-------|-------------|
| `m-1` to `m-5` | Margin (all sides) |
| `p-1` to `p-5` | Padding (all sides) |
| `mt-*`, `mb-*` | Margin top/bottom |
| `ms-*`, `me-*` | Margin start/end |
| `mx-auto` | Horizontal centering |

### Background Colors
| Class | Color |
|-------|-------|
| `bg-primary` | Blue |
| `bg-success` | Green |
| `bg-danger` | Red |
| `bg-warning` | Yellow |
| `bg-info` | Cyan |
| `bg-light` | Light gray |
| `bg-dark` | Dark gray |

### Text Classes
| Class | Effect |
|-------|--------|
| `text-center` | Center align |
| `text-muted` | Gray text |
| `fw-bold` | Bold text |
| `fs-1` to `fs-6` | Font sizes |

---

## Submission Checklist

### Part 1-6: Portfolio Website
- [ ] Portfolio displays correctly in browser
- [ ] Profile photo is visible
- [ ] Education table is properly formatted
- [ ] Website is mobile-responsive
- [ ] Code is pushed to GitHub repository

### Part 7: Bootstrap Template Customization
- [ ] Template opens correctly in browser
- [ ] Branding updated (navbar brand name changed)
- [ ] At least one dashboard card modified
- [ ] Footer updated with your information
- [ ] Modified template pushed to GitHub

### Required Screenshots for LMS
1. **Screenshot 1**: Full-page view of your portfolio in browser
2. **Screenshot 2**: GitHub repository showing pushed files
3. **Screenshot 3**: Customized Bootstrap template dashboard (Part 7)

### Caption Prompt
> Briefly explain one Bootstrap class you found most useful and why. Also describe one change you made to the Start Bootstrap template.

---

## Resources

- [Bootstrap 5 Documentation](https://getbootstrap.com/docs/5.3/)
- [Bootstrap Icons](https://icons.getbootstrap.com/)
- [Start Bootstrap - Free Templates](https://startbootstrap.com/)
- [Font Awesome Icons](https://fontawesome.com/icons)
- [W3Schools HTML Tutorial](https://www.w3schools.com/html/)
- [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/HTML)

---

## Troubleshooting

### Image not showing?
- Check the file path is correct
- Ensure the image file exists
- Use forward slashes `/` in paths

### Bootstrap styles not working?
- Verify the CDN link is correct
- Check your internet connection
- Ensure the link is inside `<head>`

### Table not displaying properly?
- Make sure all `<tr>` are inside `<thead>` or `<tbody>`
- Each row should have the same number of columns

---

**Happy Coding!**

*Part of the Deep Learning with Full Stack Deployment Course*
