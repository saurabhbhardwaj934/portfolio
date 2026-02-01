Saurabh Bhardwaj - Frontend Developer Portfolio
🎯 Overview
A modern, responsive portfolio website showcasing my skills, projects, and experience as a Frontend Developer. The website features smooth animations, interactive elements, and a clean, professional design.

✨ Features
🎨 Design & UI
Modern & Clean Interface: Professional design with elegant typography and spacing

Responsive Design: Fully responsive across all devices (mobile, tablet, desktop)

Smooth Animations: CSS animations and transitions for enhanced user experience

Interactive Elements: Hover effects, scroll animations, and dynamic content

Dark/Light Mode Ready: CSS variables for easy theme switching

📱 Sections
Hero Section

Animated title with typing effect

Professional profile image with floating shapes

Call-to-action buttons with download resume functionality

About Section

Personal introduction and professional summary

Statistics showcase

Professional image display

Skills Section

Animated skill bars with percentages

Technology icons

Progress visualization

Projects Section

Filterable project gallery

Project cards with live demo links

Technology tags for each project

Hover effects with overlay

Contact Section

Contact form with Web3Forms integration

Contact information cards

Form validation

Footer

Social media links

Back-to-top button

Copyright information

🔧 Technical Features
Form Handling: Web3Forms integration for contact form submissions

Smooth Scrolling: Navigation to sections with smooth animation

Active Navigation: Highlight current section in navigation

Mobile Navigation: Hamburger menu for mobile devices

Project Filtering: Filter projects by category

Skill Animation: Animated skill bars on scroll

🛠️ Technologies Used
Frontend
HTML5: Semantic markup

CSS3: Modern styling with Flexbox, Grid, and CSS Variables

JavaScript: Interactive functionality and animations

Font Awesome: Icon library

Google Fonts: Poppins and Montserrat fonts

Integration
Web3Forms: Contact form backend

Netlify: Project deployment and hosting

External APIs: Project links to live demos

📁 File Structure
text
portfolio/
├── index.html          # Main HTML file
├── style.css           # All styles and animations
├── script.js           # JavaScript functionality
├── Saurabh_Frontend.pdf # Resume/CV
├── srb.jpeg           # Profile image
├── professional.jpeg  # About section image
├── images/           # Project screenshots
│   ├── ecommer.png
│   ├── task.png
│   └── portfolio.png
└── README.md         # This documentation
🚀 How to Use
1. View the Portfolio
Simply open index.html in any modern web browser.

2. Navigation
Click on navigation links to scroll to sections

Use hamburger menu on mobile devices

Click "Back to Top" button in footer

3. View Projects
Browse projects in the projects section

Use filter buttons to view specific categories

Click on project images or links to view live demos

4. Contact Form
Fill in the contact form (Name, Email, Message)

Click "Send Message"

Form submissions are handled via Web3Forms

5. Download Resume
Click the "Resume" button in the hero section to download my CV.

🔗 Live Links
Portfolio Website
https://saurabhhh.netlify.app

Featured Projects
E-commerce Website: https://shophere1.netlify.app

Task Management App: https://taskmanagementt1.netlify.app

Responsive Portfolio: https://saurabhhh.netlify.app

Social Links
GitHub: https://github.com/saurabhbhardwaj934

LinkedIn: https://www.linkedin.com/in/saurabhbhardwaj009

📱 Responsive Breakpoints
Mobile: < 768px

Tablet: 768px - 1024px

Desktop: > 1024px

🎨 Customization
Colors (CSS Variables)
css
:root {
    --primary-color: #6366f1;
    --secondary-color: #10b981;
    --dark-color: #1f2937;
    --light-color: #f9fafb;
    --text-color: #374151;
}
Adding New Projects
Add project HTML structure in projects section:

html
<div class="project-card" data-category="category">
    <div class="project-image">
        <img src="images/project.jpg" alt="Project Name">
        <div class="project-overlay">
            <a href="live-demo-link" class="project-link">
                <i class="fas fa-external-link-alt"></i>
            </a>
        </div>
    </div>
    <div class="project-info">
        <h3>Project Name</h3>
        <p>Project description</p>
        <div class="project-tags">
            <span>Technology 1</span>
            <span>Technology 2</span>
        </div>
    </div>
</div>
Add corresponding image in images/ folder

Updating Skills
Modify the skills section in HTML:

html
<div class="skill-card">
    <div class="skill-icon">
        <i class="fab fa-technology-icon"></i>
    </div>
    <h3>Skill Name</h3>
    <div class="skill-bar">
        <div class="skill-level" data-level="90"></div>
    </div>
    <span class="skill-percent">90%</span>
</div>
Contact Form Configuration
The contact form uses Web3Forms. To configure:

Sign up at Web3Forms

Get your access key

Replace the access_key value in the form:

html
<input type="hidden" name="access_key" value="YOUR_ACCESS_KEY">
🛠️ Development
Local Development
Clone/download the project files

Open index.html in browser

Make changes to HTML, CSS, or JS files

Refresh browser to see changes

Browser Support
Chrome 60+

Firefox 55+

Safari 12+

Edge 79+

📝 Notes
Performance Optimization
Optimized images for web

Minified CSS and JS in production

Lazy loading for images

Efficient CSS animations

Accessibility
Semantic HTML structure

ARIA labels where needed

Keyboard navigation support

Color contrast compliance

SEO Features
Meta tags for description and keywords

Semantic heading structure

Alt text for images

📄 License
This portfolio is open source and available for personal and educational use. Please attribute appropriately if using the design.

📧 Contact
For any questions or collaboration opportunities:

Email: saurabhbhardwaj067@gmail.com

Phone: +91 8090142454

Location: Lucknow, Uttar Pradesh, India

Last Updated: December 2026
Version: 1.0.0
