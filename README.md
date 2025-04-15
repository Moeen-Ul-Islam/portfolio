# Portfolio Website

A modern, responsive portfolio website template built with HTML, CSS, and JavaScript. This portfolio showcases skills, education, work experience, certifications, and projects with a clean and professional design.

## Features

- **Responsive Design**: Works on all devices (desktop, tablet, mobile)
- **Modern UI**: Clean and professional design with smooth animations
- **Light/Dark Mode**: Toggle between light and dark themes with persistent preference
- **Separate Sections**: Home, About, Experience, Certifications, Education, Projects, and Contact
- **Interactive Skill Cards**: Visual representation of skills with icons and hover effects
- **Certification Section**: Display certifications with links to view the certificates
- **Working Contact Form**: Functional contact form that sends emails without requiring a backend
- **Smooth Scrolling**: Enhanced user experience with smooth scrolling navigation
- **Animated Timeline**: Creative timeline for education, experience, and certifications
- **Project Showcase**: Showcase your projects with images, descriptions, and links

## Project Structure

```
portfolio-website/
├── index.html              # Main HTML file
├── thanks.html             # Thank you page after form submission
├── css/
│   └── styles.css          # CSS styles
├── js/
│   └── script.js           # JavaScript functionality
├── images/                 # Images directory (placeholder images required)
│   ├── profile.jpg         # Profile photo
│   ├── about.jpg           # About section image
│   ├── project1.jpg        # Project 1 image
│   ├── project2.jpg        # Project 2 image
│   ├── project3.jpg        # Project 3 image
│   └── project4.jpg        # Project 4 image
└── README.md               # Project documentation
```

## Setup Instructions

1. **Clone or download the repository**

2. **Add your profile images**
   - Replace the placeholder images in the `images` directory with your own
   - Required images:
     - `profile.jpg`: Your profile photo for the hero section
     - `about.jpg`: Image for the About section
     - `project1.jpg` to `project4.jpg`: Images for your projects

3. **Customize the content**
   - Open `index.html` and customize the text content to match your personal information
   - Update your name, profession, bio, skills, education, experience, certifications, and projects
   - Replace the placeholder contact information with your real details

4. **Set up the contact form**
   - In `index.html`, find the contact form and replace `your-email@example.com` with your actual email address in the form action URL
   - Update the `_next` value to point to the URL where your thank you page will be hosted
   - You can customize other FormSubmit options as needed (see [FormSubmit documentation](https://formsubmit.co/))

5. **Customize the styling (optional)**
   - Open `css/styles.css` to modify the design as needed
   - You can change colors by editing the CSS variables in the `:root` selector
   - Customize the dark mode colors in the `[data-theme="dark"]` selector

6. **Deploy your website**
   - Upload the files to your web hosting or use a service like GitHub Pages, Netlify, or Vercel for free hosting

## Usage Notes

- The theme toggle allows visitors to switch between light and dark modes based on their preference
- The theme preference is saved to localStorage for a persistent experience across visits
- The contact form is set up using FormSubmit, a free service that requires no backend setup
- Project links are set to example URLs. Replace them with links to your actual GitHub repositories and live demos
- Social media links are placeholder links. Update them with your actual social media profiles
- Certification links should be updated to point to actual certificate URLs

## Additional Customization

- **Skills**: Add or remove skill cards in the skills section as needed
- **Certifications**: Add, remove, or update certifications in the certifications section
- **Colors**: Edit the CSS variables in the `:root` selector to change the light theme and in `[data-theme="dark"]` for dark theme
- **Fonts**: Replace the font family in the `body` selector to use different fonts
- **Animations**: Modify animation speeds and effects in the JavaScript file
- **Profile Picture**: Replace `images/profile.jpg` with your profile picture
- **Project Images**: Replace project images with screenshots of your own projects

## License

This template is free to use for personal and commercial projects. Attribution is appreciated but not required.

## Credits

- Font Awesome icons: [Font Awesome](https://fontawesome.com/)
- FormSubmit for form handling: [FormSubmit](https://formsubmit.co/)
- Placeholder images: Replace with your own images 