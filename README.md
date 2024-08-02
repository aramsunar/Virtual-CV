# Virtual-CV
HTML Structure
<head> Section:

Metadata and Title: Sets character encoding, viewport settings for responsiveness, and the page title.
Styles: Contains CSS styles for animating elements and defining the layout.
<body> Section:

<header>:

Contains your name, profile picture, and navigation menu.
The header uses a sticky position to remain at the top of the page and has a background color with white text.
Includes CSS animations for fading and sliding effects.
<main>:

Holds the main content sections: About Me, Resume/CV, Projects, Skills, and Contact.
About Me: Describes your background and interests, with links to your social profiles.
Resume/CV: Provides a download link for your resume and lists your courses and education.
Projects: Details various projects with descriptions and links to GitHub repositories.
Skills: Lists soft skills in a styled list format.
Contact: Shows your email and phone number.
<footer>:

Contains a copyright notice and is styled to remain at the bottom of the page with a background color matching the header.
CSS Styles
Animations:

fadeIn: Fades elements in by transitioning their opacity from 0 to 1.
slideInFromLeft and slideInFromRight: Slides elements in from the left or right side of the viewport.
General Styles:

Body: Sets the font, background color, text color, and applies a fade-in animation.
Header: Styles the background, text, and layout, with animations for fading in and sliding in elements.
Profile Picture: Styles the image with a border-radius and animation for sliding in from the left.
Navigation: Styles the navigation menu with spacing, colors, and hover effects.
Main Sections: Provides padding, background color, box-shadow, and animations for each section.
Buttons: Defines styles for buttons, including colors, padding, border radius, and hover effects.
Forms: Styles form elements, including labels, inputs, textareas, and buttons.
Footer: Styles the footer with background color, text color, and padding.
JavaScript
Smooth Scrolling:
Adds smooth scrolling behavior to navigation links. When a link is clicked, it prevents the default action and scrolls to the corresponding section with a smooth animation.