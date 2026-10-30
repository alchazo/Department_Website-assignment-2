# Assignment 2: College Department Website (HTML5)

**Author:** Chinmay T A (Roll No: 64, S7 CSEA)  
**Subject:** Web Technology / HTML Laboratory  

A multi-section, responsive, standards-compliant departmental website developed using pure **HTML5** and CSS.

## 🚀 Overview
This repository contains the design, markup, and academic documentation for a college department website (Department of Computer Science at FISAT Engineering College). It fulfills all Web Technology laboratory requirements by demonstrating standard HTML5 semantic elements, forms, tables, lists, vector graphics, and internal bookmark navigation.

## 📁 Repository Structure
```text
├── index.html                           # Complete website markup, semantic layout, and styling
├── Assignment_Report.md                 # Detailed lab documentation report & viva guide
├── Assignment-2_Report_1Page.pdf        # Single-page A4 summary report ready for submission
├── HTML_Department_Website_Report.pdf   # Alternative named copy of the 1-page report
└── README.md                            # Project documentation and quick-start instructions
```

## ✨ Key Features
- **Semantic HTML5 Architecture:** Implements `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<address>`, and `<footer>`.
- **Inline SVG Branding:** Scalable vector graphics logo in the header with high-contrast text and styling.
- **Single-Page Navigation:** Sticky navigation bar with anchor jump links (`#about`, `#programmes`, `#faculty`, `#facilities`, `#enquiry`, `#contact`).
- **Structured Lists:**
  - Unordered list (`<ul>`) displaying core curriculum specializations.
  - Ordered list (`<ol>`) outlining semester-wise academic roadmaps.
- **Tabular Faculty Directory:** Organized `<table>` with `<caption>`, `<thead>`, `<tbody>`, and alternating zebra stripes.
- **Client-Side Form Validation:** Student enquiry form with HTML5 constraints:
  - Required fields (`required`)
  - Email syntax checking (`type="email"`)
  - 10-digit phone number regex pattern (`pattern="[0-9]{10}"`)
  - Dropdown selection (`<select>`) and multi-line message area (`<textarea>`)
- **Zero External Dependencies:** Self-contained and portable — runs directly in any modern browser without npm, Node.js, or local servers.

## 💻 How to Run
1. Double-click `index.html` or right-click `index.html` -> **Open with** -> **Google Chrome** (or Microsoft Edge / Firefox).
2. The page loads instantly offline!
3. Test the features:
   - Click the navigation links at the top (About, Programmes, Faculty, Facilities, Enquiry, Contact) to jump directly between sections.
   - Scroll down to the **Student Enquiry Form** and test validation:
     - Click **Submit** with blank fields to see required field popups.
     - Type an invalid email (e.g. `test`) or phone number with fewer than 10 digits to see native HTML5 validation messages.

## 📄 Documentation & PDF Report
- [`Assignment_Report.md`](Assignment_Report.md): Full comprehensive technical report with tag breakdown.
- [`Assignment-2_Report_1Page.pdf`](Assignment-2_Report_1Page.pdf): Single-page official academic report PDF in Chinmay T A's name (Roll No. 64).
