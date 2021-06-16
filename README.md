# Overview
This file describes a project to create a developer portfolio page for the purpose of showcasing deployed software applications to prospective employers.

# Requirements

## User Story
The portfolio page development process targeted the following user story:

```
AS AN employer
I WANT to view a potential employee's deployed portfolio of work samples
SO THAT I can review samples of their work and assess whether they're a good candidate for an open position
```

## Acceptance Criteria
The following acceptance criteria were identified as requirements for successful completion of the portfolio page:

```
GIVEN I need to sample a potential employee's previous work

1. WHEN I load their portfolio
- THEN I am presented with the developer's name, a recent photo or avatar, and links to sections about them, their work, and how to contact them

2. WHEN I click one of the links in the navigation
- THEN the UI scrolls to the corresponding section

3. WHEN I click on the link to the section about their work
- THEN the UI scrolls to a section with titled images of the developer's applications

4. WHEN I am presented with the developer's first application
- THEN that application's image should be larger in size than the others

5. WHEN I click on the images of the applications
- THEN I am taken to that deployed application

6. WHEN I resize the page or view the site on various screens and devices
- THEN I am presented with a responsive layout that adapts to my viewport
```

# Contents

## HTML
To fulfill the above requirements, semantic html tags were used to create an HTML file with:
- A header containing the developer name and a navigation bar
- A banner image section with a subtitle
- A main section containing "About Me", "Work" and "Contact Me" sections, each of which is accessible via the links in the header navigation bar
  - The "About Me" section currently contains placeholder text, which will be replaced with a substantive developer profile at a later date.
  - Similarly, the "Work" section contains placeholder images for 5 development projects, with a "top" application showcased prominently above 4 smaller projects. Each of the project titles currently links to a wikipedia page as a placeholder.
  - Finally, the "Contact Me" section contains placeholder contact information, which also links to Wikipedia pages as placeholders, with the exception the GitHub link, which points to the developer's page on the GitHub site.

## CSS
- A CSS stylesheet was created to give the portfolio page a modern design, and a consistent color schema
- The CSS file also includes styling for a responsive layout that will adapt to narrow viewports, such as a smartphone, tablet, or resized desktop window
- Sectioning and comments were added to the CSS file to make the file more navigable and understandable

# Deployed Application

## Link to Deployed Application
The live portfolio page can be accessed at the following link: 
https://j1741.github.io/hw_02_portfolio/

## Screenshot of Deployed Application
The following screenshot of the deployed application illustrates the results of the portfolio page development process: 
![Alt text](./screenshot.png?raw=true "Screenshot Of Portfolio Page")