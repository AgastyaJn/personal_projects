# Personal Portfolio Website

A modern, responsive personal portfolio website to showcase your skills, projects, and contact information.

## Features

- Responsive design that works on all devices
- Clean and modern UI with smooth animations
- Sections for About, Skills, Projects, and Contact
- Contact form for visitors to reach out
- Social media links
- Mobile-friendly navigation

## How to Customize

### 1. Personal Information

Edit the `index.html` file to update:

- Your name (replace "Your Name" throughout the document)
- Job title/description in the hero section
- About Me section content
- Contact information (email, phone, location)
- Social media links (GitHub, LinkedIn, etc.)

### 2. Skills

Modify the skills section in `index.html` to reflect your technical skills. Each skill is represented by a card with an icon and title. You can add or remove skills as needed.

### 3. Projects

Update the projects section with your own projects. For each project:
- Add a project image to the `img` folder
- Update the image path in the HTML
- Change the project title and description
- Update the technology tags
- Add links to GitHub repository and live demo

### 4. Images

Replace the placeholder images with your own:
- Add your profile picture as `profile.jpg` in the `img` folder
- Add project screenshots as `project1.jpg`, `project2.jpg`, etc.

### 5. Resume

Add your resume as a PDF file named `resume.pdf` in the root directory for the download link to work.

### 6. Colors

To change the color scheme, edit the CSS variables in the `:root` selector in `css/style.css`:

```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #1e40af;
    --dark-color: #1f2937;
    --light-color: #f3f4f6;
    --success-color: #10b981;
    --danger-color: #ef4444;
    --max-width: 1200px;
}
```

## Deployment

To make your portfolio accessible online, you can deploy it using GitHub Pages:

1. Create a new repository on GitHub
2. Push your portfolio code to the repository
3. Go to Settings > Pages
4. Select the main branch as the source
5. Your portfolio will be published at `https://yourusername.github.io/repository-name/`

You can then add this URL to your CV as a link to your portfolio.

## Credits

- Font Awesome for icons
- Google Fonts for the Poppins font
- Inspiration from various portfolio designs
