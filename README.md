# landing_page
**Task** – Responsive Landing Page for a Tech Product (Precollete Global Limited Website) 

**Overview**
This project is a fully responsive, modern landing page for Precollete Global Limited, a technology company specializing in software development, cloud computing, AI, cybersecurity, IoT, and data analytics. The website is designed to showcase the company's services, pricing plans, testimonials, and frequently asked questions (FAQ) while providing an engaging user experience with dynamic features like a sticky header, dark mode toggle, and interactive elements.
The website is built using vanilla HTML, CSS, and JavaScript, ensuring lightweight performance and cross-browser compatibility. It is optimized for all devices, from mobile phones to desktops, and includes accessibility considerations to enhance usability.

✨ **Features**
1. **Dynamic Header Behavior**
  •	The header is sticky and remains at the top when scrolling up, providing easy access to navigation.
  •	The header hides when scrolling down to maximize screen real estate and reappears when scrolling up.
  •	Navigation links include smooth hover effects and are fully responsive, stacking vertically on smaller screens.
2. **Dark Mode Toggle**
  •	A toggle button allows users to switch between light and dark themes.
  •	Dark mode changes the appearance of the header, content sections, testimonials, pricing plans, about us, FAQ, and footer with specific styling:
  o	Header: Black background, white text, and a blue border-bottom (#007bff).
  o	Content, Ads, Pricing Plans, FAQ, Footer: Black background with white text and blue borders.
  o	Our Solutions, Testimonial, About Us: Dark gray background (#1E1E1E) with white text and blue borders.
  o	FAQ Items: Dark gray background with white borders and text.
  •	Theme preference is saved in localStorage to persist across page reloads.
  •	The toggle button icon switches between a moon (light mode) and a sun (dark mode).
3. **Responsive Design**
  •	The website is fully responsive, adapting to various screen sizes (mobile, tablet, desktop) using CSS media queries.
  •	Flexbox is used for flexible layouts, with sections stacking vertically on smaller screens.
  •	Font sizes, padding, and margins are scaled using rem, vw, and percentages for consistency.
  •	Images are responsive with width: 100% and height: auto to prevent overflow.
  •	Navigation and footer sections adjust for mobile usability, ensuring a seamless experience.
4. **Interactive Sections**
  •	Content Section: Highlights the company's no-code landing page creation tool with a call-to-action button.
  •	Our Solutions: Lists services like software development, cloud computing, AI, and more, with a clickable link for additional details.
  •	Ads Slider: A carousel showcasing different services (AI, cloud, cybersecurity, IT consulting) with previous/next buttons and auto-sliding every 3 seconds.
  •	Testimonials: Displays client feedback in a card-based layout, with responsive design for mobile devices.
  •	Pricing Plans: Features a toggle for monthly/yearly pricing, with dynamic price updates and a "Most Popular" badge for the Professional plan.
  •	About Us: Encourages users to explore payment processing solutions with prominent call-to-action buttons.
  •	FAQ: An accordion-style section with expandable answers, featuring plus/minus icons for interactivity.
5. **Footer**
  •	Includes social media links, product/resources/company navigation, and legal links.
  •	Responsive design ensures the footer is usable on all devices, with sections stacking on mobile.

**Technologies Used**
•	HTML5: Semantic markup for structure and accessibility.
•	CSS3: Custom properties (:root, [data-theme="dark"]) for theming, Flexbox for layouts, and media queries for responsiveness.
•	JavaScript (Vanilla): Handles dynamic features like the header scroll behavior, dark mode toggle, FAQ accordion, ads slider, and pricing toggle.
•	SVG Icons: Used for the dark mode toggle and social media links, ensuring crisp visuals.
•	LocalStorage: Persists the user's theme preference across sessions.

**Installation**
1.	Clone the repository:
2.	https://github.com/agalageorge/landing_page.git 
3.	Navigate to the project directory:
4.	cd precollete-global-limited
5.	Open index.html in a web browser to view the website locally. Alternatively, serve it using a local server (e.g., with Live Server in VS Code or http-server).

**Project Structure**
precollete-global-limited/
├── images/                 # Image assets (logo.png, tech3.jpg, etc.)
├── index.html             # Main HTML file
└── README.md              # This file
Note: Ensure all image paths in index.html match the actual file locations in the images/ directory.

**Usage**
•	Header Navigation: Click links to jump to sections (Our Solutions, Testimonials, Pricing Plans, About Us, FAQ).
•	Dark Mode: Click the moon/sun icon in the header to toggle between light and dark themes.
•	Ads Slider: Use the "Previous" and "Next" buttons to navigate the carousel, or let it auto-slide.
•	Pricing Toggle: Switch between monthly and yearly pricing to see updated prices (yearly plans offer a 25% discount).
•	FAQ: Click on a question to expand/collapse the answer.
•	Responsive Testing: Resize the browser or use developer tools to test responsiveness across devices.

**Future Improvements**
•	Accessibility: Add ARIA attributes for screen readers, especially for the dark mode toggle and FAQ accordion.
•	Image Optimization: Use modern formats like WebP or implement lazy loading for faster page loads.
•	Animations: Add subtle animations for section transitions or hover effects to enhance user engagement.
•	Backend Integration: Connect to a backend for dynamic content (e.g., fetching testimonials or pricing data).
•	SEO: Improve meta tags and structured data for better search engine visibility.

**Contributing**
Contributions are welcome! To contribute:
1.	Fork the repository.
2.	Create a new branch (git checkout -b feature/your-feature).
3.	Make your changes and commit (git commit -m "Add your feature").
4.	Push to the branch (git push origin feature/your-feature).
5.	Open a pull request with a detailed description of your changes.
Please ensure your code follows the project's coding style and includes appropriate tests.
License
This project is licensed under the MIT License. See the LICENSE file for details.
Contact
For questions or feedback, contact the project maintainer at agalageorge91@gmail.com or open an issue on GitHub.
