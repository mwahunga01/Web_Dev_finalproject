# Personal Portfolio Website (HTML + CSS + Vercel Deployment)
## Author: Brian M. Mwahunga
## Project Title: My Personal Portfolio Website
## Technologies Used: HTML5, CSS3, Vercel
## Date Completed: 21st November 2025
 ### 1. Project Overview

This project involved designing, developing, and deploying a fully responsive personal portfolio website using only HTML and CSS, without any external libraries. The website highlights my skills, professional experience, academic qualifications, and geospatial engineering projects.

The final website is deployed on Vercel, a cloud platform for static site hosting.

The goal of this assignment was to:

Build a visually appealing and professional portfolio site.

Structure the content based on my actual CV.

Use clean, readable, and maintainable HTML & CSS.

Demonstrate understanding of folder structure, semantic markup, and responsive design.

Deploy a real project to Vercel successfully.

### 2. Project Files Structure

The project contains only two items:

my-portfolio/
│── index.html      # Main webpage
│── style.css       # Styling file



The minimal structure ensures clarity and adheres to the requirement of using only HTML and CSS.

### 3. Step-by-Step Development Process
#### 3.1 Planning & Wireframing

Before writing any code, I planned the website layout and identified key sections required in a personal portfolio:

Hero Section – Name, title, contact links

About Me – Professional summary

Skills – Technical and soft skills grouped in cards

Experience – Work & internship experience

Projects Portfolio – Four key geospatial projects

Education & Certifications

Contact Information

Footer


#### 3.2 Creating index.html

I wrote a clean, semantic HTML structure using:

header - for the introduction

section - elements for logical content grouping

footer - for copyright

ul and li for lists

div - wrappers for grid layouts

Key points:

The hero section uses headings and styled anchor tags for email, LinkedIn, and phone.

Projects and skills use grid layouts (defined later in CSS).

No external libraries were used.

#### 3.3 Creating style.css

The CSS file controls the entire presentation.
Key design principles applied:

##### 3.3.1 Responsive Design

Used grid-template-columns: repeat(auto-fit, minmax(...)) for flexible layouts.

Ensured spacing using consistent padding and margins.

##### 3.3.2 Consistent Colour Palette

The hero banner uses a dark professional gradient:

background: linear-gradient(to bottom right, #0a0a23, #1c1c46);


This creates a clean and modern aesthetic.

##### 3.3.3 Typography

Sans-serif fonts for readability.

Clear hierarchy using different font sizes and weights.

##### 3.3.4 Card-Based UI

Skills, projects, and experience are presented using “cards”:

Rounded corners

Light backgrounds

Left border highlights

Hover-friendly colors

This improves clarity and visual appeal.

### 4. Deployment Process on Vercel

I deployed the website on Vercel, a platform designed for fast static hosting.

#### 4.1 Creating the GitHub Repository

Logged into GitHub and created a new repository named my-portfolio.

Uploaded index.html and style.css.

Ensured the root directory contained both files (no subfolders required).

#### 4.2 Connecting to Vercel

Logged in to Vercel using GitHub.

Clicked “New Project”.

Selected my portfolio repository.

Vercel automatically detected it as a static HTML project.

Clicked Deploy.

#### 4.3 Deployment Outcome

Vercel built and deployed the website automatically.
A live URL was generated, which can be used for:

Showcasing my work

Portfolio reviews

Job/attachment applications

Academic assessment

### 5. Skills Practised During the Task
#### Front-End Development

HTML5 semantic structuring

CSS3 layout design

Responsive grid design

Hero banners & visual hierarchy

#### Software Engineering Workflow

File organisation

Use of version control (GitHub)

Deployment on Vercel

Documentation (this README)

#### Professional Branding

Translating a CV into an online presence

Curating content for industry relevance

#### 6. Challenges Faced & Solutions
Challenge 1: Ensuring the UI is modern using only CSS

Solution:
Used gradients, grids, and card layouts to achieve a clean design without needing libraries.

Challenge 2: Keeping the site fully responsive

Solution:
Used flexible CSS grids with auto-fit and minmax(), avoiding fixed pixel layouts.

Challenge 3: Deployment configuration

Solution:
Since Vercel auto-detects static sites, no configuration files were necessary.

### 7. Conclusion

This project successfully demonstrates my ability to:

Design and build a functional, visually appealing, and professional website

Work strictly within HTML + CSS constraints

Translate CV material into structured web content

Deploy a full project using modern deployment tools

Document the development process comprehensively
