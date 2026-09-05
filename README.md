# Web Resume & Systems Portfolio

A multi-page web resume and portfolio for CS 651 Web Systems.

## Project Structure

```text
web-resume/
├── Templates/
│   └── resume-template.dwt   # Master Dreamweaver Template (Layout, Header, Nav, Footer)
├── styles.css                 # External CSS (HTML tag styles & named class styles)
├── index.html                 # Overview & Executive Summary
├── experience.html            # Work Experience (Docker, ThoughtSpot, Cloudera)
├── projects.html              # Technical Projects & System Architecture
├── skills.html                # Categorized Skills, Frameworks & Enterprise Platforms
├── education.html             # CSUEB (MS in CS) & CSUS (BS in CS)
├── contact.html               # Contact information & interactive message form
└── resume.html                # Single-page resume (from Lab F1.1)
```

## Lab Compliance Notes

### LAB F2.1 - Multi-Page Resume Using Templates
- **Master Template:** [`Templates/resume-template.dwt`](Templates/resume-template.dwt) defines the site layout, master header (without photo), main navigation, editable regions (`<!-- TemplateBeginEditable name="MainContent" -->`), and footer.
- **Instance Pages:** All pages (`index.html`, `experience.html`, `projects.html`, `skills.html`, `education.html`, `contact.html`) use standard Dreamweaver template instance markup (`<!-- InstanceBegin -->`, `<!-- InstanceBeginEditable -->`).
- **Seamless Navigation:** Every page shares the same responsive navigation bar, with the active tab highlighted.

### LAB F3.1 - External Stylesheet (`styles.css`)
- **Tag Styles:** Global defaults for `body`, `h1`-`h4`, `p`, `a`, `ul`, `ol`, `li`, `hr`, `input`, `textarea`, and `button`.
- **Named Styles:** Custom CSS classes including `.resume-wrapper`, `.site-header`, `.site-nav`, `.nav-link`, `.page-title`, `.section-title`, `.lead-text`, `.content-card`, `.card-top`, `.date-pill`, `.stats-grid`, `.stat-box`, `.badge`, `.contact-layout`, and `.btn-primary`.
- **Responsive & Print-Friendly:** Includes media queries for mobile/tablet screens and `@media print` rules for clean printing.
