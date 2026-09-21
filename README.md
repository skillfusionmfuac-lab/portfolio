# Sofia - Academic Portfolio

A clean, professional, and minimalist personal portfolio website for **Sofia**, a university lecturer and chemistry researcher.

The website focuses on presenting Sofia's academic background, teaching philosophy, research experience, and professional profile in a simple and elegant interface.

## About

Sofia is a dedicated university lecturer passionate about bridging the gap between complex theoretical concepts and real-world scientific applications.

With a strong background in **chemistry**, she aims to create dynamic and inclusive classrooms and laboratories that encourage active participation and critical thinking.

Her teaching philosophy is based on the idea that education is a collaborative journey. Rather than only teaching foundational chemical principles, she focuses on helping students develop the analytical and experimental skills required to solve complex problems and innovate within the sciences.

Before entering academia full-time, Sofia worked in applied chemical research, gaining practical laboratory and industry experience that she now brings into her teaching.

Her current research focus can be customized based on her specific field, such as:

* Green Chemistry
* Organic Synthesis
* Materials Science
* Chemical Research
* Sustainable Chemistry

Her goal is to empower the next generation of scientists to approach challenges with curiosity, confidence, creativity, and a passion for lifelong learning.

---

## Project Goals

The portfolio should:

* Present Sofia's academic and professional profile.
* Highlight her chemistry background.
* Communicate her teaching philosophy.
* Showcase research interests and experience.
* Provide a professional online presence.
* Use a clean and minimalist academic design.
* Be responsive across desktop, tablet, and mobile devices.
* Maintain excellent readability and accessibility.

---

## Technology

This project should use **HTML and CSS only**.

### Technologies

* HTML5
* CSS3
* Google Sans
* Responsive Web Design

### Restrictions

Do **not** use:

* JavaScript
* React
* Vue
* Angular
* Bootstrap
* Tailwind CSS
* Other CSS frameworks
* External UI libraries

The website should be implemented using only standard HTML and CSS.

---

## Design System

### Primary Color

```text
#E3E3E3
```

The primary color should be used carefully throughout the interface while maintaining strong contrast and readability.

### Typography

Use **Google Sans** as the primary typeface.

Example:

```css
font-family: 'Google Sans', sans-serif;
```

The typography should feel:

* Modern
* Professional
* Academic
* Clean
* Highly readable

### Visual Style

The overall design should follow a:

* Minimalist aesthetic
* Professional academic appearance
* Clean layout
* Generous whitespace
* Clear typography hierarchy
* Subtle borders
* Simple navigation
* Responsive layout

Avoid unnecessary visual effects.

Do not use:

* Excessive gradients
* Heavy shadows
* Glassmorphism
* Neon colors
* Overly decorative elements
* Excessive animations
* Cluttered layouts

---

## Folder Structure

```text
portfolio/
│
├── assets/
│   └── images/
│       ├── icon/
│       │   └── icon.ico
│       │
│       └── me_photo.jpg
│
├── index.html
│
└── README.md
```

---

## Assets

### Profile Photo

```text
assets/images/me_photo.jpg
```

Use this image as Sofia's main profile photograph.

The image should be displayed professionally, preferably using a clean rectangular or subtly rounded presentation depending on the final design.

### Website Icon

```text
assets/images/icon/icon.ico
```

Use this file as the website favicon.

Example:

```html
<link rel="icon" type="image/x-icon" href="assets/images/icon/icon.ico">
```

---

## Website Structure

The portfolio should contain the following main sections.

### 1. Navigation

Create a simple navigation bar containing:

* Sofia's name or logo
* About
* Research
* Teaching
* Experience
* Contact

The navigation should remain clean and responsive.

---

### 2. Hero Section

The hero section should immediately introduce Sofia.

Suggested content:

**Sofia**

**University Lecturer & Chemistry Researcher**

Short introduction:

> Bridging scientific knowledge, practical research, and meaningful education.

Include the profile image from:

```text
assets/images/me_photo.jpg
```

The hero section should provide a strong but minimal first impression.

---

### 3. About Me

Include the following profile information:

> As a dedicated university lecturer, I am passionate about bridging the gap between complex theoretical concepts and real-world scientific application. With a strong background in chemistry, I strive to create dynamic, inclusive classrooms and laboratories that encourage active participation and critical thinking.

Continue with her teaching philosophy and academic goals.

The section should clearly communicate:

* Academic background
* Teaching philosophy
* Student-centered education
* Analytical thinking
* Experimental learning
* Scientific innovation

---

### 4. Research

Create a research section highlighting Sofia's scientific interests.

Use editable placeholder content for the specific research field:

```text
[Insert specific focus]
```

Possible examples:

* Green Chemistry
* Organic Synthesis
* Materials Science
* Sustainable Chemistry

The design should allow additional research topics or projects to be added later.

---

### 5. Teaching Philosophy

Create a dedicated section explaining Sofia's approach to education.

Key themes:

* Collaborative learning
* Critical thinking
* Laboratory-based learning
* Scientific curiosity
* Problem solving
* Active participation
* Inclusive education
* Lifelong learning

The section should feel personal rather than like a generic university profile.

---

### 6. Academic / Professional Experience

Create an experience timeline or structured list.

Possible categories:

```text
University Lecturer
Applied Chemical Researcher
Laboratory Research
Academic Projects
```

Each item should support:

* Position
* Institution
* Date
* Description
* Key responsibilities

Use placeholder content where exact information is not yet available.

---

### 7. Skills & Expertise

Create a clean section displaying relevant academic and scientific expertise.

Possible categories:

**Chemistry**

* Chemical Analysis
* Laboratory Techniques
* Organic Chemistry
* Materials Science

**Teaching**

* University Teaching
* Laboratory Instruction
* Curriculum Development
* Student Mentoring

**Research**

* Applied Chemical Research
* Experimental Design
* Scientific Analysis
* Research Methodology

Only include skills that are confirmed later.

---

### 8. Contact

Create a simple contact section.

Possible information:

```text
Email
University
Research Profile
LinkedIn
```

The contact area should remain minimal and easy to use.

---

## Responsive Design

The website must work properly on:

* Desktop
* Laptop
* Tablet
* Mobile

Use CSS media queries where necessary.

Example:

```css
@media (max-width: 768px) {
    /* Mobile and tablet styles */
}
```

The layout should adapt naturally rather than simply shrinking the desktop version.

---

## Accessibility

The portfolio should follow basic accessibility practices.

Use:

* Semantic HTML5 elements
* Proper heading hierarchy
* Descriptive `alt` text
* Keyboard-accessible navigation
* Sufficient color contrast
* Readable font sizes
* Clearly identifiable links and buttons

Example:

```html
<img
    src="assets/images/me_photo.jpg"
    alt="Sofia, university lecturer and chemistry researcher"
>
```

---

## Code Quality

Keep the HTML and CSS:

* Clean
* Semantic
* Well organized
* Easy to maintain
* Properly indented
* Free of unnecessary code

Use meaningful class names.

Example:

```html
<section class="about-section">
    <div class="about-content">
        ...
    </div>
</section>
```

Avoid inline CSS where possible.

---

## Development Instructions

1. Create the project folder.

2. Create the required directory structure:

```text
assets/
└── images/
    ├── icon/
    └── me_photo.jpg
```

3. Add the profile image:

```text
assets/images/me_photo.jpg
```

4. Add the favicon:

```text
assets/images/icon/icon.ico
```

5. Create:

```text
index.html
```

6. Build the complete portfolio using only HTML and CSS.

7. Use Google Sans for typography.

8. Use `#E3E3E3` as the primary color.

9. Test the website on desktop and mobile screen sizes.

---

## Claude Development Instructions

This project is intended to be developed with **Claude**.

When modifying the project, Claude should:

* Inspect the existing files before making changes.
* Preserve the existing folder structure.
* Use only HTML and CSS.
* Avoid introducing JavaScript unless explicitly requested.
* Avoid unnecessary dependencies.
* Keep the design minimalist and professional.
* Maintain responsive behavior.
* Reuse existing assets where appropriate.
* Keep the code easy for a beginner to understand.
* Make changes directly related to the requested feature.
* Avoid replacing working sections unnecessarily.

When adding new content, maintain the same visual language and typography throughout the website.

---

## Content Customization

The following information should be replaced with Sofia's actual information when available:

```text
[Insert specific focus]
[University Name]
[Academic Position]
[Research Area]
[Email Address]
[LinkedIn Profile]
[Research Profile]
```

Do not invent academic qualifications, research publications, institutions, awards, or professional experience.

---

## License

This portfolio is a personal website project.

Content, photographs, and personal information belong to their respective owner.
