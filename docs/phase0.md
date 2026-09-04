
# Project Phase 0 — Website Content and Semantic HTML Structure

## Client Website Development Project

You have been assigned a client who needs a new website for their organization.

You are working as a **junior web developer** responsible for building the client's website from the requirements provided by the client.

In a professional web development environment, developers normally do not begin by choosing colors, adding animations, or experimenting with visual effects.

Before visual design begins, the development team must first determine:

* what information belongs on the website,
* how that information should be organized,
* what pages are required,
* how visitors will navigate between pages,
* which HTML elements best describe the meaning of the content,
* and whether the website structure is understandable before styling is applied.

Your first project deliverable is therefore the **content and semantic HTML foundation** of the client's website.

---

# Your Role

For this project, assume that you have been hired as a:

> **Junior Front-End Web Developer**

Your instructor will act as the:

> **Client / Project Manager**

The business assigned to you is your client for the remainder of the semester.

You are responsible for interpreting the client requirements and developing the website through several project phases.

Future phases will build upon the code you create now.

**Do not treat each phase as a separate website.**

You will continue improving the same project throughout the semester.

---

# Client Assignments

| Student | Client Project                  |
| ------- | ------------------------------- |
| Nicole  | North Woods Coffee Company      |
| Eleanor | Pine & Paws Pet Grooming        |
| Sarah   | Riverbend Music Academy         |
| Ketsia  | Katahdin Trail & Paddle         |
| Alex    | Northern Bloom Floral & Events  |
| Shane   | Harbor Light Books & Stationery |
| Richard | Cedar & Stone Home Services     |
| Gab     | Maine Makers Workshop           |

Your client brief contains the specific business information, audience, required pages, services, products, events, or other content required for your website.

---

# Client Situation

The client has approved the **general website content and required pages**, but the website has not yet been designed.

At this stage of the project, the client wants to review the organization and completeness of the website before approving visual design work.

Your task is to produce an **unstyled HTML prototype**.

The prototype should allow the client to answer questions such as:

* Is all important information included?
* Is the website organized logically?
* Can visitors find the information they need?
* Are the page names understandable?
* Does the navigation work?
* Is the content grouped correctly?
* Does each page have a clear purpose?

The client is **not reviewing colors, fonts, animations, or visual styling yet**.

---

# Phase 0 Objective

Build the complete HTML content structure for your assigned client website using **HTML5 semantic elements**.

By the end of this phase, your website should function as a complete content-based website even though it has little or no visual styling.

Think of this phase as building the **structure of a house before painting or decorating it**.

---

# Scope of Work

During this phase you will:

1. Review the client requirements.
2. Identify the required pages.
3. organize the information for each page.
4. Create the website folder and file structure.
5. Build all required HTML pages.
6. Create consistent site navigation.
7. Use semantic HTML5 elements.
8. Add the required client content.
9. Create a consistent header and footer.
10. Test every navigation link.
11. Validate the HTML.
12. Publish your progress to GitHub.

---

# Important Project Rule

## Build From the Client Requirements

You are not creating a website for yourself.

Every major content decision should be based on the requirements provided by your client.

You may improve wording or organization when necessary, but you may not:

* change the business,
* remove required services,
* remove required pages,
* replace required information,
* invent major services not requested by the client,
* change client contact information,
* or redesign the project into a different type of business.

If information is required by the client, it must appear somewhere appropriate on the website.

---

# Step 1 — Review the Client Brief

Before writing HTML, carefully review the project requirements in your repository.

Identify:

### Business Information

Determine:

* business name,
* type of business,
* client contact,
* location if provided,
* target customers,
* and overall business goal.

### Required Pages

Identify every page requested by the client.

### Required Content

Identify the content that must appear on each page.

Examples may include:

* services,
* products,
* menu items,
* lessons,
* instructors,
* workshops,
* events,
* rental equipment,
* packages,
* service areas,
* business hours,
* contact information,
* or calls-to-action.

Do not begin coding until you understand what information the website must contain.

---

# Step 2 — Plan the Information Architecture

Professional websites need an organized information structure.

Before creating the pages, determine how visitors will move through the website.

Your primary navigation should include all major pages requested by the client.

For example:

```text
Home
About
Services
Projects
Contact
```

Your project will have different navigation items depending on your assigned client.

The navigation should remain consistent across all pages.

---

# Step 3 — Create the Website File Structure

Organize your repository using a professional folder structure.

A recommended starting structure is:

```text
project-folder/
│
├── index.html
├── about.html
├── other-required-page.html
├── other-required-page.html
├── contact.html
│
├── css/
│   └── style.css
│
├── js/
│   └── script.js
│
├── images/
│
└── README.md
```

Your filenames should:

* use lowercase letters,
* avoid spaces,
* use meaningful names,
* and remain consistent.

### Good filenames

```text
index.html
about.html
services.html
contact.html
guided-trips.html
```

### Avoid filenames such as

```text
Page1.html
My Page.html
FINALPAGE.html
test2.html
```

The `css` and `js` folders may remain mostly unused during this phase.

They are being created now because they will be needed in later development phases.

---

# Step 4 — Build Every Required HTML Page

Every page requested by the client must exist during Phase 0.

A page should not simply contain:

```html
<h1>Coming Soon</h1>
```

Each page must contain the required client content.

For example, if your client requires a Services page containing five services, all five services should already appear in the HTML.

If your client requires event information, the events should already exist.

If your client requires products or menu items, they should already be included.

---

# Step 5 — Use a Complete HTML Document Structure

Every HTML page must contain the basic HTML5 document structure.

Example:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Page Title | Business Name</title>
</head>

<body>

</body>
</html>
```

Every page must have a meaningful `<title>`.

Do not use:

```html
<title>Document</title>
```

Instead use titles such as:

```html
<title>Services | Cedar & Stone Home Services</title>
```

or:

```html
<title>Lessons | Riverbend Music Academy</title>
```

---

# Step 6 — Use Semantic HTML

HTML should describe the **meaning and purpose of content**, not only how it should eventually look.

You are expected to use HTML5 semantic elements appropriately.

Common semantic elements include:

```html
<header>
<nav>
<main>
<section>
<article>
<aside>
<footer>
```

Other meaningful HTML elements include:

```html
<h1>
<h2>
<h3>

<p>

<ul>
<ol>
<li>

<address>

<figure>
<figcaption>

<a>

<strong>
<em>
```

Use the element that best describes the content.

---

# Required Overall Page Structure

Most pages should follow a structure similar to:

```html
<body>

    <header>
        <!-- Business identity -->

        <nav>
            <!-- Main website navigation -->
        </nav>
    </header>

    <main>

        <!-- Page-specific content -->

    </main>

    <footer>
        <!-- Business and website information -->
    </footer>

</body>
```

Do not place the entire website inside a collection of meaningless `<div>` elements when semantic elements are available.

---

# Header Requirement

Every page must contain a site header.

The header should identify the client business.

Example:

```html
<header>
    <a href="index.html">
        North Woods Coffee Company
    </a>

    <nav>
        ...
    </nav>
</header>
```

The exact content will depend on your assigned project.

---

# Navigation Requirement

All required website pages must be accessible through the primary navigation.

Example:

```html
<nav aria-label="Main navigation">
    <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="about.html">About</a></li>
        <li><a href="services.html">Services</a></li>
        <li><a href="contact.html">Contact</a></li>
    </ul>
</nav>
```

Your navigation links must work.

Do not use links such as:

```html
<a href="#">Services</a>
```

when the Services page already exists.

---

# Main Content Requirement

Each page should contain one primary `<main>` element.

Example:

```html
<main>

    <section>
        ...
    </section>

    <section>
        ...
    </section>

</main>
```

The content inside `<main>` should represent the unique content of that page.

---

# Heading Structure

Use headings to create a meaningful hierarchy.

Each page should normally contain one primary `<h1>`.

Example:

```html
<h1>Our Services</h1>
```

Major sections may use:

```html
<h2>Carpentry Repairs</h2>
```

Subsections may use:

```html
<h3>Common Repair Projects</h3>
```

Avoid selecting headings because of their default visual size.

Do not jump randomly between heading levels simply because one appears larger or smaller.

The structure:

```text
H1
 ├── H2
 │    └── H3
 ├── H2
 │    └── H3
```

communicates the organization of the document.

CSS will control how headings look later.

---

# Section Requirement

Use `<section>` when content represents a meaningful section of the page.

Example:

```html
<section>
    <h2>Our Services</h2>

    ...
</section>
```

A section should usually contain a heading that explains its purpose.

---

# Article Requirement

Use `<article>` when content could reasonably stand as an individual item.

Examples include:

* service descriptions,
* instructor profiles,
* workshop listings,
* events,
* book listings,
* menu items,
* guided trips,
* project examples.

Example:

```html
<article>
    <h3>Deck Maintenance</h3>

    <p>
        Seasonal inspection and maintenance services for
        residential decks.
    </p>
</article>
```

---

# Lists

Use lists when information represents a true group of related items.

For example:

```html
<ul>
    <li>Bangor</li>
    <li>Brewer</li>
    <li>Hampden</li>
    <li>Orono</li>
    <li>Old Town</li>
</ul>
```

Do not create a series of paragraphs when a list would more accurately describe the information.

---

# Contact Information

When appropriate, contact information may use the `<address>` element.

Example:

```html
<address>
    <p>Marcus Hale</p>
    <p>Phone: <a href="tel:+12075550107">207-555-0107</a></p>
    <p>
        Email:
        <a href="mailto:marcus@cedarstonehome.example">
            marcus@cedarstonehome.example
        </a>
    </p>
</address>
```

Use the exact contact information provided in your client requirements.

---

# Footer Requirement

Every page must contain a footer.

At minimum, include:

* business name,
* contact information when appropriate,
* and copyright information.

Example:

```html
<footer>
    <p>&copy; 2026 Cedar & Stone Home Services</p>
</footer>
```

The footer should be consistent throughout the website.

---

# Images

You may begin adding appropriate images during this phase if suitable assets are available.

Every meaningful image must contain useful alternative text.

Example:

```html
<img
    src="images/coffee-shop.jpg"
    alt="Freshly brewed coffee served on a wooden café table"
>
```

Do not use filenames as alternative text.

Avoid:

```html
alt="coffee1.jpg"
```

Do not use meaningless descriptions such as:

```html
alt="image"
```

If an image is purely decorative, it may use:

```html
alt=""
```

---

# Content Quality

Client websites should contain believable content.

Avoid obvious placeholder text such as:

```text
Lorem ipsum dolor sit amet...
```

Do not write:

```text
This is our about page.
```

Instead, create content appropriate for the client's business using the information and requirements provided in the client brief.

---

# Calls-to-Action

A **call-to-action**, or CTA, tells the visitor what action to take next.

Examples include:

```text
Request an Appointment
Find Your Instrument
Request a Quote
View Our Workshops
Explore Rentals
```

If your client brief specifies a particular CTA, use the required wording.

A CTA should normally link to an appropriate page.

Example:

```html
<a href="contact.html">Request a Quote</a>
```

Visual button styling will be added in a later phase.

---

# Do Not Focus on Visual Design Yet

During Phase 0, do **not** spend significant time creating:

* color palettes,
* custom fonts,
* elaborate layouts,
* animations,
* hover effects,
* responsive grids,
* JavaScript interactions,
* sliders,
* carousels,
* complex menus.

Those requirements belong to later phases.

The website may look plain.

That is expected.

The goal of this phase is:

> **Correct structure before visual presentation.**

---

# Accessibility Foundation

Accessibility begins with HTML structure.

During this phase, make sure that:

* the document language is identified,
* headings follow a logical hierarchy,
* navigation uses real links,
* images contain appropriate `alt` attributes,
* contact links are meaningful,
* lists use list elements,
* buttons are not simulated using plain text,
* semantic elements are used where appropriate.

Good HTML reduces the amount of accessibility repair needed later.

---

# HTML Comments

Use comments where they help identify major areas of the document.

Example:

```html
<!-- Site Header -->

<header>
    ...
</header>

<!-- Main Content -->

<main>
    ...
</main>

<!-- Site Footer -->

<footer>
    ...
</footer>
```

Do not comment every individual HTML element.

Comments should help another developer understand the organization of the code.

---

# Code Formatting

Professional code should be readable.

Indent nested elements consistently.

### Good

```html
<section>
    <h2>Our Services</h2>

    <article>
        <h3>Carpentry Repairs</h3>
        <p>Residential carpentry repair services.</p>
    </article>
</section>
```

### Avoid

```html
<section><h2>Our Services</h2><article><h3>Carpentry Repairs</h3><p>Residential carpentry repair services.</p></article></section>
```

Another developer should be able to open your files and quickly understand their structure.

---

# GitHub Development Workflow

Your repository represents the project's development history.

Do not upload the entire completed phase as one final commit.

Commit your work as you develop it.

Examples of meaningful commit messages:

```text
Create initial site file structure

Add main navigation to all pages

Build homepage semantic structure

Add client services content

Create About page

Complete contact information

Fix navigation links

Improve heading hierarchy

Validate HTML pages
```

Avoid commit messages such as:

```text
stuff

update

asdf

final

final2

done
```

A professional development history should communicate what changed.

---

# Recommended Development Sequence

A reasonable workflow is:

```text
1. Review client requirements

2. Create required files and folders

3. Create basic HTML document structure

4. Build shared header

5. Build navigation

6. Build shared footer

7. Build Home page

8. Build About page

9. Build remaining client pages

10. Add required client content

11. Review semantic HTML

12. Test navigation

13. Validate HTML

14. Push final Phase 0 work to GitHub
```

---

# Quality Assurance Check

Before submitting the phase, test the website as if you were another developer reviewing your work.

Verify the following.

## Files

* [ ] `index.html` exists.
* [ ] Every client-required page exists.
* [ ] File names are meaningful.
* [ ] File names use consistent lowercase formatting.
* [ ] Required project folders exist.

## HTML

* [ ] Every page contains `<!DOCTYPE html>`.
* [ ] Every page identifies the document language.
* [ ] Every page contains the viewport meta tag.
* [ ] Every page has a meaningful `<title>`.
* [ ] HTML elements are properly nested.
* [ ] Code indentation is consistent.

## Semantic Structure

* [ ] `<header>` is used appropriately.
* [ ] `<nav>` identifies site navigation.
* [ ] `<main>` identifies primary page content.
* [ ] `<section>` is used for meaningful page sections.
* [ ] `<article>` is used where appropriate.
* [ ] `<footer>` appears on every page.
* [ ] Lists use `<ul>` or `<ol>` where appropriate.

## Headings

* [ ] Every page has a clear primary heading.
* [ ] Heading hierarchy is logical.
* [ ] Headings are not selected based only on visual size.

## Navigation

* [ ] Every required page appears in the navigation.
* [ ] All navigation links work.
* [ ] Navigation is consistent across pages.
* [ ] There are no unnecessary `href="#"` links.

## Client Content

* [ ] All client-required information is included.
* [ ] Required services/products/events are present.
* [ ] Client name is correct.
* [ ] Client email is correct.
* [ ] Client phone number is correct.
* [ ] Required CTAs use the correct wording.
* [ ] Placeholder text has been removed.

## Accessibility

* [ ] Images have appropriate alternative text.
* [ ] Links contain understandable text.
* [ ] Semantic HTML is used where possible.
* [ ] Page structure makes sense without CSS.

---

# Client Review Scenario

At the end of this phase, assume that your HTML prototype is being presented to the client.

The client is reviewing the website primarily for:

### Content Completeness

> Is the information I requested actually present?

### Content Organization

> Is the information located where visitors would expect to find it?

### Navigation

> Can visitors easily move between the major sections of the website?

### Business Accuracy

> Does the website accurately represent my organization?

### Future Development Readiness

> Is the HTML organized well enough for the design team to begin styling it?

You should be able to explain your decisions if the client asks why particular information appears on a particular page.

---

# Phase 0 Deliverables

Submit the following.

## 1. GitHub Repository

Your repository must contain the current website source code.

---

## 2. Complete HTML Website

All client-required pages must be included.

---

## 3. Semantic HTML Structure

The website must demonstrate appropriate use of HTML5 semantic elements.

---

## 4. Client Content

All required Phase 0 client information must appear in the website.

---

## 5. Working Navigation

All required pages must be accessible from the site's primary navigation.

---

## 6. Git Commit History

Your repository must demonstrate incremental development through meaningful commits.

---

## 7. Published Website

Publish the current version of the website using **GitHub Pages**.

The website does not need to look finished.

The published site is being used as a **development preview** for the client.

---

# Submission

Submit the following in Canvas:

```text
GitHub Repository URL:

GitHub Pages Website URL:
```

Example:

```text
GitHub Repository:
https://github.com/username/project-name

GitHub Pages:
https://username.github.io/project-name/
```

Before submitting, open both URLs yourself and verify that they work.

---

# Definition of Done

Phase 0 is complete when:

> A client can open the published website, navigate through every required page, read the required business content, and understand the overall organization of the website even though visual styling has not yet been developed.

The HTML created during this phase will become the foundation for the next stage of development.

---

# What Happens Next?

Once the client approves the website structure and content, the project can move into the next development phase.

The next phase will focus on turning the plain HTML prototype into a deliberate visual design using CSS.

You should **not rebuild the website from the beginning**.

You will continue developing the same files created during Phase 0.

Your existing:

* HTML structure,
* navigation,
* content,
* headings,
* sections,
* articles,
* images,
* and client information

will become the foundation for the visual design.

This is how a real web development project evolves:

```text
Client Requirements
        ↓
Content Planning
        ↓
Information Architecture
        ↓
Semantic HTML Prototype
        ↓
Client Review
        ↓
Visual Design and CSS
        ↓
Responsive Development
        ↓
Interactivity
        ↓
Testing
        ↓
Deployment
```

**Phase 0 establishes the foundation. Do not move forward with a weak foundation.**
