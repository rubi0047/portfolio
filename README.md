# Sam Rubinoff’s Portfolio Website

## Live Site  
Check out the live version of this portfolio here:  
[https://rubi0047.github.io/portfolio/](https://rubi0047.github.io/portfolio/)

---

## Table of Contents
- [Introduction](#introduction)
- [Goal of the Portfolio](#goal-of-the-portfolio)
- [What the Site Showcases](#what-the-site-showcases)
- [Planning and Design Approach](#planning-and-design-approach)
- [Tools Used](#tools-used)
- [HTML, CSS, and Media Query Structure](#html-css-and-media-query-structure)
- [Accessibility and Semantic HTML](#accessibility-and-semantic-html)
- [Development Challenges](#development-challenges)
- [What I Learned](#what-i-learned)
- [Soft Skills Gained](#soft-skills-gained)
- [Assets and Resources Used](#assets-and-resources-used)

---

## Introduction

Welcome to my personal web portfolio. This site is a space where I can showcase my creative work, connect with potential collaborators or clients, and keep all my professional content in one organized and stylish place. I built it to take ownership of my work and create something that represents me beyond a static resume or social media profile.

Having a digital portfolio is more than just a nice touch. It's a valuable tool that shows what I can do, how I approach projects, and how I present myself online. It also gives me the freedom to grow and update my presence as I take on new experiences. This site was built with intention, a lot of learning, and a focus on clean design and usability.

---

## Goal of the Portfolio

The goal of this portfolio is pretty simple. I wanted to give people a clear, professional, and creative look at what I do. I built it to feel personal but still polished, so anyone visiting can quickly understand my skills and style. Whether someone is hiring, looking to collaborate, or just checking out my work, this site makes it easy to explore and connect. Every part of it was made to reflect how I work and what I bring to the table.

---

## What the Site Showcases

This portfolio is built to highlight the kind of visual work I do and make it easy for people to explore or reach out. The main content is visual, from photos to design work, and every link on the site leads to external platforms like Google Drive or Instagram. Keeping everything off-site helps the site stay lean, fast, and easy to update whenever I want. I can drop new work into a folder or post, and it's immediately available without needing to touch the site code.

All of the icon work was created by me using Figma and Photoshop. The photos of me were taken by either myself or my partner. Every main image on the site is fully responsive, with at least three versions depending on screen size. In a lot of cases, there are even more than that.

The contact form is fully functional. When someone fills it out and hits submit, it opens their email client with everything they typed pre-filled into the message and a subject line that reads "Contact from Website." It keeps the experience simple for the user and avoids needing a back-end.

The entire site is designed to scale across devices. Whether someone is visiting from a phone, a tablet, or a desktop, the layout stays clean and easy to use.

---

## Planning and Design Approach

I started by mapping out what I actually needed the site to do. I didn’t want to overcomplicate things, so the focus was always on clarity and usability. I sketched out some basic layouts first, then moved into Figma to build out a proper wireframe and visual reference. From there, I translated that design into code, always keeping mobile-first in mind.

Visually, I wanted the site to feel clean but personal. That meant sticking to a consistent color palette and typography system while letting the visuals do most of the talking. Every section is there for a reason, and I tried to keep the experience as focused as possible. The design decisions were guided by function just as much as style.

---

## Tools Used

I used a mix of design and development tools to bring everything together. Figma was my starting point for wire-framing and layout planning. Photoshop and Illustrator handled all the visual assets, from icons to touchups. I built the site in VS Code, which kept everything organized and easy to manage.

For layout and responsiveness, I primarily used Bootstrap to handle the grid system and breakpoints. It helped speed things up and kept everything consistent across devices. I also used Hover.css to add small interactive touches without bloating the site. Derivv.com came in handy for testing how the site looked across different screens. Every tool I used helped streamline the process and keep the workflow focused.

---

## HTML, CSS, and Media Query Structure

I kept the HTML as clean and semantic as possible. Every section is clearly labeled and uses appropriate tags so it’s easy to follow and accessible. I used main, section, header, and footer tags where they made sense, and kept everything organized with meaningful class names.

For the CSS, I used root variables to stay consistent with color, spacing, typography, and font sizes. This made it way easier to make global changes without digging through the whole stylesheet. I kept things modular and reusable whenever possible, and made sure the custom styles worked alongside Bootstrap without clashing.

Media queries were written with a mobile-first approach. I started with the smallest screen sizes and worked my way up. I focused on key breakpoints like 480px, 834px (iPad Pro), and 1450px (MacBook Air), making sure the layout scaled smoothly across all of them. Every major image also has multiple responsive sizes to make sure it loads clean and fast on any device.

---

## Accessibility and Semantic HTML

Accessibility was something I kept in mind from the start. I used semantic HTML wherever possible so that screen readers and other assistive tools could navigate the site properly. Things like using header, main, and footer tags, structuring content with proper heading levels, and labeling interactive elements all help with that.

I also used aria-labels and microdata where it made sense, especially around navigation and contact areas. The goal was to make sure the site isn’t just nice to look at, but also easy to use for everyone. It’s not perfect, but I made a real effort to keep things as accessible and readable as I could.

---

## Development Challenges

One of the biggest challenges was making sure everything stayed responsive across devices. Getting things to look right on desktop is one thing, but translating that to tablet and mobile without breaking layout took a lot of fine-tuning. I used Bootstrap’s grid system and wrote custom media queries where needed to keep things flexible. Testing through derivv.com helped me catch layout shifts early.

Another challenge was organizing my CSS in a way that didn’t get messy as the project grew. I used root variables for all my colors, spacing, fonts, and sizes, which made things way easier to manage. It also helped keep the style consistent across every page without needing to rewrite the same values over and over.

The contact form was also tricky. I wanted it to be functional without needing a backend, and also avoid using JavaScript. I ended up using the mailto: approach, but customized it so that it pulls in everything the user types and pre-fills the email with a subject line. It’s a simple solution that works, and it let me keep the form fully accessible and easy to use.

---

## What I Learned

Building this portfolio taught me a lot, especially when it comes to writing cleaner, more efficient code. I got more comfortable using semantic HTML and organizing CSS with root variables to keep things consistent. I also learned how to properly use Bootstrap alongside my own custom styles without letting one override the other. You can see my Contact Page for an example of my progress as I worked through the site. It was the last page I worked on, and it was structurally the best of the four.

Working with responsive layouts gave me a better understanding of how to structure media queries and when to let Bootstrap handle things versus when to write my own CSS. I also got more familiar with writing markdown for documentation, which has been super helpful for keeping everything organized and clear for anyone looking at the project later.

---

## Soft Skills Gained

This project pushed me to slow down and really pay attention to the details. I found myself double-checking spacing, testing across screen sizes, and refining things I might’ve let slide in the past. It definitely helped sharpen my eye for design consistency and usability.

Problem-solving was a big part of the process too. Whether it was figuring out a layout issue or troubleshooting weird rendering bugs, I had to stay patient and keep digging until things worked the way I wanted. It reminded me that figuring things out is half the job, and that being able to troubleshoot effectively is just as important as writing the code itself.

---

## Assets and Resources Used

Here’s a list of assets and resources I used throughout the site that aren’t my own. I used each one intentionally to keep the site lightweight, functional, and easy to update.

### Fonts (via [Google Fonts](https://fonts.google.com/))
- [Lobster Two](https://fonts.google.com/specimen/Lobster+Two)
- [Nunito Sans](https://fonts.google.com/specimen/Nunito+Sans)
- [Quattrocento Sans](https://fonts.google.com/specimen/Quattrocento+Sans)

### Frameworks & Libraries
- [Bootstrap](https://getbootstrap.com/)
- [Hover.css](https://ianlunn.github.io/Hover/)

### External Platforms
- [Google Drive](https://drive.google.com)
- [Instagram](https://www.instagram.com/samraphone)
- [YouTube](https://www.youtube.com/@ksamrubinoff)

### Design
- [Figma Prototype](https://www.figma.com/design/dq74AuT0KJSLdv81pwKt9O/s-rubinoff-interactive-prototype?node-id=180-105&t=wRN3XJa5lGscmkbG-1)

---

© Sam Rubinoff  
Created: April 9th, 2025