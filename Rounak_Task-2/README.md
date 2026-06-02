Rounak Shekhar - Animated Personal Portfolio Website
Overview

This project is a fully responsive personal portfolio landing page built using HTML5 and CSS3. The website introduces Rounak Shekhar, a Computer Science student and aspiring software developer, through an interactive and modern user interface.

The portfolio features multiple CSS animations, including:

Animated loading bars
Typing text effect
Rotating circular image border
Smooth content reveal animations
Interactive social media buttons
Modern dark-themed design
Live Features
Navigation Bar

The fixed navigation bar contains:

Portfolio Logo
Home
About
Portfolio
Service
Contact
Animation

The navigation bar is initially hidden and appears after the page loading animation using:

animation: show-content .5s linear forwards;
animation-delay: 1.2s;
Animated Background Loading Effect

Before the portfolio content appears, six animated bars slide down from the top of the screen.

HTML Structure
<div class="bars-animation">
    <div class="bar"></div>
</div>
CSS Animation
@keyframes show-bars {
    100% {
        transform: translateY(0%);
    }
}
Purpose

Creates a professional page-entry effect similar to modern portfolio websites.

Hero Section

The homepage is divided into two sections:

Left Side

Contains:

Name
Profession Animation
Personal Introduction
Contact Information
Download CV Button
Social Media Icons
Right Side

Contains:

Circular Profile Image
Rotating Neon Border Animation
Personal Information Displayed
Name
Rounak Shekhar
Dynamic Roles

The portfolio alternates between:

Web Developer
Student

using CSS-only text animation.

Career Objective

The portfolio introduces Rounak as:

B.Tech Computer Science Student
Future Software Developer
Web Development Learner
DSA in Java Learner
Typing Text Animation

The profession section uses a CSS typing effect.

Example
<span data-text="Web Developer">
Animation Sequence
Web Developer appears.
Text is typed letter-by-letter.
Text disappears.
Student appears.
Process repeats infinitely.
CSS Animations Used
@keyframes display-text
@keyframes fill-text
Contact Information Section

The website displays:

Phone Number
+91 62993 83620
Email Address
mrexcellent37@gmail.com
Styling

Contact labels are highlighted using:

color: #7cf03d;

to match the website's neon-green theme.

Download CV Button
Features
Rounded shape
Neon glow effect
Hover animation
Default Style
background: #7cf03d;
Hover Effect
background: transparent;
color: #7cf03d;
Social Media Section

The portfolio contains social icons for:

GitHub
LinkedIn
Twitter
YouTube
Icon Library

The project uses Boxicons classes:

bx bxl-github
bx bxl-linkedin
bx bxl-twitter
bx bxl-youtube
Hover Effect

Icons change color and glow when hovered.

Profile Image Section
Circular Image Container

The profile image is displayed inside a perfect circle.

Structure
<div class="img-box">
    <div class="img-item">
        <img src="Rounak.png">
    </div>
</div>
Rotating Border Animation

One of the main highlights of the website.

Effect

A neon-green border rotates continuously around the profile image.

Technology Used
background: conic-gradient(...)
Animation
@keyframes rotate-border {
    100% {
        transform: rotate(360deg);
    }
}
Rotation Speed
4 seconds
Infinite Loop
Color Palette
Purpose	Color
Background	#1f242d
Accent Green	#7cf03d
Text	#ffffff
Border Glow	#7cf03d
Typography
Font Family
Poppins

Imported from Google Fonts:

@import url('https://fonts.googleapis.com/css2?family=Poppins');
CSS Techniques Used
Flexbox

Used for:

Navigation layout
Home section layout
Image alignment
Button and social icon alignment
Example
display: flex;
justify-content: space-between;
align-items: center;
Animations Included
Animation	Purpose
show-content	Reveals navbar and content
show-bars	Page loading effect
display-text	Role switching
fill-text	Typing effect
rotate-border	Rotating image ring
Project Structure
Portfolio-Website/
│
├── index.html
├── style.css
├── Rounak.png
└── README.md
Technologies Used
Frontend
HTML5
CSS3
CSS Features
Flexbox
Keyframe Animations
Conic Gradient
Hover Effects
CSS Variables
Responsive Units (vw)
External Resources
Google Fonts (Poppins)
Boxicons
Current Functionality

✅ Animated Navigation Bar

✅ Loading Screen Bar Animation

✅ Dynamic Profession Text

✅ Typing Text Effect

✅ Contact Information Section

✅ Download CV Button

✅ Social Media Icons

✅ Circular Profile Image

✅ Rotating Border Ring

✅ Neon Hover Effects

✅ Dark Modern Theme