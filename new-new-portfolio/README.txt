Student Name: Jayvee Reyes
Project: Portfolio Website
Topic: Personal Coding Journey (C# & Fullstack Web Development)

=============================================================================
1. TOPIC CHOICE
=============================================================================
I chose to build a professional portfolio website focusing on my academic journey as a Computer Science student specializing in C# and ASP.NET Core. 

This topic allows me to:
- Showcase my specific technical skills (Backend Architecture, Entity Framework).
- Present my academic projects ("eTourMoElyu" and "FreshPath") in a structured format.
- Demonstrate my ability to write semantic HTML and cleaner CSS without relying on frameworks like Bootstrap.

=============================================================================
2. KEY DESIGN DECISIONS
=============================================================================
To meet the requirement for a professional and responsive design, I made the following decisions:

A. Color Scheme
   - I utilized a primary color of Dark Blue (#2c3e50) to convey professionalism and stability.
   - A Bright Blue accent (#3498db) is used for interactive elements (buttons, links) to guide the user's eye.
   - The background is kept Light Gray (#ecf0f1) to reduce eye strain and ensure high readability.

B. Layout & Typography
   - I used a "Sticky/Absolute" Header design. The header is positioned absolutely (top: 0), floating over the content to maximize screen real estate.
   - To prevent content from being hidden behind this floating header, I applied top padding to the body element.
   - Fonts: 'Segoe UI' is used for body text for modern readability, while 'Georgia' (serif) is used for headings to add a classic, academic touch.

C. Navigation
   - The menu uses a Flexbox layout to space links evenly.
   - An "active" class was implemented in CSS to visually underline the link of the page the user is currently viewing, helping with orientation.
   - Responsive Design: A media query at 768px breaks the flex layout into a column, making the navigation stack vertically on mobile devices for easier tapping.

D. CSS Effects
   - Hover States: All links and buttons smoothly transition colors over 0.3 seconds.
   - Box Shadows: Content sections have a subtle shadow to lift them off the page, creating depth.
   - Circular Profile Image: On the About page, the profile picture uses a 50% border-radius to create a perfect circle with a thick accent border.

=============================================================================
3. FORM STRUCTURES
=============================================================================
Both forms are built using semantic HTML5 tags and validated using the 'required' attribute.

A. Contact Form (contact.html)
   - Purpose: Simple inquiry submission.
   - Structure:
     - <input type="text"> for the Name.
     - <input type="email"> for the Email Address (validates for @ symbol).
     - <textarea> for the Message body.
     - A submit button styled with CSS transitions.

B. Registration Form (register.html)
   - Purpose: Newsletter sign-up with specific user data.
   - Structure:
     - Date of Birth: Uses <input type="date"> to provide a native calendar picker.
     - Interest Level: Uses <input type="radio"> grouped by the 'name' attribute ("level") so users can only select one option (Beginner, Intermediate, or Expert).
     - Terms Agreement: Uses <input type="checkbox"> with the 'required' attribute, preventing form submission unless checked.

=============================================================================
4. FILE LIST
=============================================================================
- index.html      (Home Page)
- about.html      (About Me)
- contact.html    (Contact Page)
- register.html   (Sign Up Page)
- style.css       (Global Stylesheet)
- README.txt      (Project Documentation)
- /assets/        (Folder containing images)