CreativeDev Portfolio Landing Page

A simple and elegant personal portfolio landing page created using HTML5 and CSS3. This project introduces Rounak Shekhar, a student and web developer, through a modern hero section featuring a profile image, navigation menu, and call-to-action button.
📖 Project Description

This landing page serves as a personal portfolio homepage. It contains:
A navigation bar with menu links
A hero section with an introduction
A circular profile image with a hover animation
A dark-themed modern design

The project is designed to be lightweight, beginner-friendly, and easy to customize for personal branding.

📂 Project Structure
Portfolio-Landing-Page/
│
├── index.html        # Main HTML file
├── style.css         # Styling file
├── rounak.png        # Profile image
└── README.md         # Project documentation
🖥️ Preview Layout
Navigation Bar

The top navigation bar contains:

CreativeDev logo
Home link
About link
Services link
Contact link
<nav class="navbar">

The navigation bar uses Flexbox to align the logo and menu items horizontally.

Hero Section

The hero section is divided into two parts:

Left Side

Contains:

Main heading
Personal introduction
"Get In Touch" button
<div class="hero-content">

Displayed Text:

Welcome to my Portfolio

I am Rounak Shekhar. I am a Student and a Web Developer. I am ready to be in the game of today's life competition.

Right Side

Contains a circular profile image.

<div class="hero-image">

The image is displayed inside a white circular container.

<div class="image-circle">
    <img src="rounak.png" alt="Profile Image">
</div>
🎨 Styling Details
Background Colors
Element	Color
Body Background	#221f36
Navbar Background	#3b2a7d
Text Color	White
Image Circle Background	White
Flexbox Layout

The project uses Flexbox extensively:

Navbar
display: flex;
justify-content: space-between;
Hero Section
display: flex;
justify-content: space-between;
align-items: center;

This creates a clean two-column layout.

Circular Profile Image

The profile image is wrapped inside a circular container:

.image-circle{
    width: 380px;
    height: 380px;
    border-radius: 50%;
}

The image itself is also circular:

.image-circle img{
    border-radius: 50%;
}
Hover Animation

When the user hovers over the profile image:

.image-circle img:hover{
    transform: scale(1.03);
}