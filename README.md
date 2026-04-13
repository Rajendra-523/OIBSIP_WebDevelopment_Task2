# OIBSIP Web Development Task 2
## Personal Portfolio Project

This project is a modern and responsive personal portfolio website created using HTML, CSS, and JavaScript as part of the Oasis Infobyte Web Development Internship. The main goal of this task is to understand how a professional portfolio webpage is structured with HTML, how it is styled with CSS, and how JavaScript is used to add interactivity and animations.

The website is designed as a single-page portfolio for **BURLAGADAA RAJENDRA**. It includes a navigation bar, hero section, about section, skills section, project showcase, certificates section, contact form, and footer. This project is useful for beginners and intermediate learners who want to practice frontend web development by building a complete portfolio website.

## Author Details

Name: BURLAGADAA RAJENDRA  
Internship: Oasis Infobyte  
Domain: Web Development and Designing  
Task: Level 1 - Task 2

## Technologies Used

HTML5 for the structure of the webpage  
CSS3 for styling, layout design, and responsiveness  
JavaScript for animations, interactivity, and dynamic effects

## Project Structure

`rajendra_portfolio.html` - Contains the complete structure and content of the portfolio website  
`style.css` - Contains all the styles used for layout, colors, typography, spacing, animations, and responsive design  
`script.js` - Contains the JavaScript used for cursor effects, typing animation, scroll reveal, active navigation, form feedback, and counters  
`README.md` - Contains the project explanation and details

## HTML Explanation

The `rajendra_portfolio.html` file defines the complete structure of the portfolio website. It is divided into several important sections:

### 1. Document Setup

The file starts with the `<!DOCTYPE html>` declaration, which tells the browser that the document uses HTML5. Inside the `<head>` section:

`<meta charset="UTF-8">` sets the character encoding  
`<meta name="viewport" content="width=device-width, initial-scale=1.0">` helps the page scale properly on different screen sizes  
`<title>` sets the page title shown in the browser tab  
The project also includes styling and scripting for a complete portfolio experience

### 2. Navigation Bar

The `<nav>` section creates the fixed top navigation bar. It includes:

A logo area with the text `BR.`  
A menu with links such as About, Skills, Projects, Certificates, and Contact  
A "Hire Me" button linked to email

This section gives the page a professional header and allows users to move quickly between sections.

### 3. Hero Section

The hero section is the first main section of the webpage. It includes:

A tag showing availability for work  
The portfolio owner name  
Animated professional role text  
A short introduction paragraph  
Action buttons such as "View My Work" and "Get In Touch"  
Animated statistics like projects built, certificates, and tech stacks  
A profile image area with a badge

This section creates a strong first impression and introduces the portfolio clearly.

### 4. About Section

The About section introduces the developer in more detail. It includes:

A personal introduction  
Background in full stack development  
Information cards for location, availability, specialization, and languages  
Frontend, backend, and database/tool summaries

This section helps visitors understand the developer profile and technical background.

### 5. Skills Section

The project contains a dedicated skills section with multiple skill cards. Each card highlights an important area such as:

Frontend Development  
Backend Development  
Database and Cloud  
Tools and Workflow  
Programming Languages  
Soft Skills

These cards are useful for presenting technical abilities in a clean and organized way.

### 6. Projects Section

The Projects section showcases a featured project. It includes:

Project number and name  
Project description  
Technology stack used  
Feature list  
Buttons for live demo and GitHub

This section is important because it demonstrates practical development experience.

### 7. Certificates Section

The Certificates section displays learning achievements in card format. Each card contains:

Certificate number  
Certificate title  
Issuer name  
Year  
Verification text

This section adds credibility to the portfolio.

### 8. Contact Section

The Contact section is designed for communication. It includes:

A short collaboration message  
Email, WhatsApp, and Instagram contact links  
A contact form with name, email, and message fields  
A submit button

This section makes the portfolio useful for networking, freelance work, and job opportunities.

### 9. Footer

The `<footer>` section is placed at the bottom of the page. It contains a copyright message and social shortcut links. This gives the page a complete and finished look.

## CSS Explanation

The `style.css` file is responsible for the visual appearance of the portfolio website.

### 1. Body Styling

The `body` selector sets the main font, background colors, text color, and overall base styling. The design uses a dark modern theme to give the portfolio a professional look.

### 2. Root Variables

The `:root` section stores reusable color variables such as:

Background color  
Surface color  
Card color  
Border color  
Accent colors  
Text colors

This makes the stylesheet easy to manage and update.

### 3. Navbar Styling

The `nav` section uses:

`display: flex`  
`justify-content: space-between`  
`align-items: center`

These properties arrange the logo, links, and button in a horizontal row. The blurred dark background and accent colors improve the visual style.

### 4. Hero Section Styling

The hero section uses grid layout, spacing, glow background effects, and bold typography. The headings are large and eye-catching, while the buttons are styled with strong colors and hover effects.

The hero area also includes:

Glowing background elements  
Animated profile frame  
Stats cards  
Button styling with hover transitions

This makes the top section visually strong and modern.

### 5. Cards and Section Layout

The project uses both Grid and Flexbox for layouts. These are used in:

About section  
Skills cards  
Project section  
Certificate cards  
Contact layout  
Footer elements

Cards are styled using:

Background color  
Padding  
Borders  
Hover effects  
Transitions  
Shadows and visual highlights

This makes each section look clear and attractive.

### 6. Typography and Colors

The project uses imported fonts to create a stylish portfolio design. Different font styles are used for headings and body text. Accent colors are used to highlight important text, buttons, and interactive elements.

### 7. Animations and Effects

The CSS also supports several visual effects such as:

Blinking text cursor effect  
Hover transitions  
Reveal transitions  
Animated border rotation around the profile image  
Custom cursor styling  
Background glow and noise overlay

These effects improve the overall user interface.

### 8. Responsive Design

The project includes media queries for smaller screen sizes. These adjust the layout by:

Changing two-column sections into one-column layout  
Reducing image and spacing sizes  
Stacking certificate cards vertically  
Making the footer mobile-friendly

This ensures the portfolio works well on desktop, tablet, and mobile devices.

## JavaScript Explanation

The `script.js` file is responsible for interactivity and dynamic behavior in the portfolio website.

### 1. Custom Cursor Effect

JavaScript tracks mouse movement and updates a custom cursor dot and ring on the screen. This creates a unique interactive effect for the portfolio.

### 2. Hover Cursor Animation

When the user hovers over links, buttons, skill cards, certificate cards, or project cards, the cursor changes size and color. This gives better user feedback.

### 3. Typed Text Animation

The script creates a typing effect for roles such as:

Full Stack Developer  
MERN Stack Engineer  
React Developer  
Node.js Backend Dev

The text is typed and deleted repeatedly to create an animated introduction.

### 4. Scroll Reveal Effect

JavaScript uses `IntersectionObserver` to detect when elements appear in the viewport. When they become visible, the elements are revealed with smooth transitions.

### 5. Active Navigation Highlight

The script checks the current scroll position and highlights the navigation link for the section currently being viewed. This improves navigation and user experience.

### 6. Contact Form Feedback

The contact form currently uses a simulated submission process. When the form is submitted:

The default refresh action is prevented  
The button text changes to indicate success  
The button color changes temporarily  
The original button text returns after a short delay

This gives interactive feedback without needing a backend.

### 7. Counter Animation

The statistics in the hero section animate from `0` to their target values when the section comes into view. This makes the portfolio more engaging.

## Features of the Project

Modern and responsive portfolio website  
Clean single-page layout using HTML, CSS, and JavaScript  
Fixed navigation bar with section links  
Hero section with animated role text  
About section with personal information  
Skills cards for technical categories  
Featured project showcase  
Certificates display section  
Contact section with contact form  
Custom cursor interaction  
Scroll reveal effects  
Animated counters in the hero section  
Responsive design for multiple devices

## How to Run the Project

Download or clone the project folder.  
Open the folder in your code editor.  
Open `rajendra_portfolio.html` in any web browser.  
No additional setup, framework, or installation is required because this project is built with HTML, CSS, and JavaScript.

## Learning Outcome

By completing this task, the following concepts can be understood more clearly:

Structuring a complete portfolio website using HTML  
Styling sections with CSS  
Using colors, spacing, cards, and typography effectively  
Applying Grid and Flexbox for layout design  
Making a responsive webpage for different screen sizes  
Adding interactivity using JavaScript  
Creating animations like typing effect, reveal effect, and counters  
Building a professional personal portfolio page
# demo video
demo video link:

## Conclusion

This project is a strong portfolio-based frontend task for learning web development. It shows how HTML creates the structure of a webpage, how CSS improves the design and layout, and how JavaScript adds interactivity and animations. The portfolio website is modern, readable, responsive, and useful for practicing core frontend concepts in a real project.
