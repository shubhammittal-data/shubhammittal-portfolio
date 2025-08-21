# Personal Portfolio - HTML5UP Massively Theme

A professional portfolio website built using the HTML5UP Massively theme. This portfolio showcases your skills, projects, experience, and provides multiple ways for potential clients or employers to contact you.

## 🚀 Features

- **Responsive Design** - Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX** - Clean, professional design with smooth animations
- **Multiple Sections** - About, Projects, Skills, Experience, and Contact pages
- **Contact Forms** - Easy way for visitors to get in touch
- **Social Media Integration** - Links to your professional profiles
- **SEO Optimized** - Proper meta tags and structure for search engines

## 📁 File Structure

```
portfolio/
├── index.html          # Home/About page
├── projects.html       # Projects showcase
├── skills.html         # Skills and technologies
├── experience.html     # Work experience and education
├── contact.html        # Contact information and forms
├── assets/
│   ├── css/           # Stylesheets
│   ├── js/            # JavaScript files
│   └── sass/          # SASS source files
└── images/            # Your portfolio images
```

## 🛠️ Customization Guide

### 1. Personal Information

Replace all instances of `[Your Name]` with your actual name throughout the files:

- `index.html` - Lines 7, 25, 35
- `projects.html` - Lines 7, 25, 35
- `skills.html` - Lines 7, 25, 35
- `experience.html` - Lines 7, 25, 35
- `contact.html` - Lines 7, 25, 35

### 2. Contact Information

Update your contact details in all files:

- **Email**: Replace `[your.email@example.com]` with your actual email
- **Phone**: Replace `[Your Phone Number]` with your phone number
- **Address**: Replace `[Your City, State]` and `[Your Country]` with your location

### 3. Social Media Links

Update the social media links in the navigation and footer sections:

```html
<li><a href="YOUR_LINKEDIN_URL" class="icon brands fa-linkedin"><span class="label">LinkedIn</span></a></li>
<li><a href="YOUR_GITHUB_URL" class="icon brands fa-github"><span class="label">GitHub</span></a></li>
<li><a href="YOUR_TWITTER_URL" class="icon brands fa-twitter"><span class="label">Twitter</span></a></li>
<li><a href="YOUR_INSTAGRAM_URL" class="icon brands fa-instagram"><span class="label">Instagram</span></a></li>
```

### 4. Projects Section

Update the projects in `index.html` and `projects.html`:

1. **Project Images**: Replace `images/pic01.jpg` through `images/pic07.jpg` with your actual project screenshots
2. **Project Titles**: Update project names and descriptions
3. **Technologies**: List the actual technologies used in each project
4. **Links**: Add real links to live demos and source code

### 5. Skills Section

Customize the skills in `skills.html`:

- **Frontend**: Update with your actual frontend skills
- **Backend**: List your backend technologies
- **Mobile**: Include your mobile development experience
- **DevOps**: Add your infrastructure and deployment skills
- **Data**: Include data processing and analytics skills

### 6. Experience Section

Update `experience.html` with your actual work history:

- **Job Titles**: Replace with your actual positions
- **Companies**: Update company names
- **Dates**: Use your actual employment dates
- **Achievements**: List your real accomplishments
- **Education**: Update with your actual education details

### 7. Images

Replace the placeholder images in the `images/` folder:

- `pic01.jpg` - Your profile photo or hero image
- `pic02.jpg` through `pic07.jpg` - Project screenshots or relevant images

## 🎨 Design Customization

### Colors
The theme uses a dark color scheme. To customize colors, edit `assets/css/main.css` or the SASS files in `assets/sass/`.

### Typography
Fonts are defined in the CSS files. You can change fonts by updating the font-family properties.

### Layout
The layout is responsive and uses CSS Grid and Flexbox. Major layout changes should be made in the SASS files.

## 📱 Mobile Optimization

The portfolio is fully responsive and optimized for:
- Desktop (1200px+)
- Tablet (736px - 1199px)
- Mobile (735px and below)

## 🚀 Deployment

### Option 1: GitHub Pages (Free)
1. Create a GitHub repository
2. Upload your portfolio files
3. Go to Settings > Pages
4. Select source branch (usually `main`)
5. Your site will be available at `https://yourusername.github.io/repository-name`

### Option 2: Netlify (Free)
1. Sign up for Netlify
2. Drag and drop your portfolio folder
3. Your site will be live instantly
4. You can add a custom domain later

### Option 3: Vercel (Free)
1. Sign up for Vercel
2. Connect your GitHub repository
3. Deploy automatically on every push

## 🔧 Local Development

To run the portfolio locally:

1. Download or clone the files
2. Open `index.html` in your web browser
3. Or use a local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx serve .
   
   # Using PHP
   php -S localhost:8000
   ```

## 📝 Content Guidelines

### Writing Your Bio
- Keep it concise but engaging
- Highlight your unique value proposition
- Include your passion for technology
- Mention your career goals

### Project Descriptions
- Focus on the problem you solved
- Highlight the technologies used
- Include metrics when possible (performance improvements, user numbers)
- Add links to live demos and source code

### Skills Organization
- Group related skills together
- Use consistent formatting
- Include proficiency levels if desired
- Keep it updated with current technologies

## 🎯 SEO Optimization

The portfolio includes basic SEO elements:

- Proper title tags
- Meta descriptions
- Semantic HTML structure
- Alt text for images
- Clean URLs

## 📞 Contact Form Setup

The contact forms are currently set to `action="#"`. To make them functional:

1. **Formspree** (Free):
   ```html
   <form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
   ```

2. **Netlify Forms**:
   ```html
   <form name="contact" method="POST" data-netlify="true">
   ```

3. **Custom Backend**: Set up your own server to handle form submissions

## 🔄 Updates and Maintenance

- Keep your projects section updated with new work
- Regularly update your skills as you learn new technologies
- Add new experiences and certifications
- Update contact information as needed
- Refresh images periodically

## 📄 License

This portfolio is based on the HTML5UP Massively theme, which is free for personal and commercial use under the Creative Commons license.

## 🤝 Support

If you need help customizing your portfolio:

1. Check the HTML5UP documentation
2. Review the CSS/SASS files for styling options
3. Use browser developer tools to experiment with changes
4. Consider hiring a developer for complex customizations

---

**Happy coding!** 🚀

Your portfolio is now ready to showcase your skills and attract new opportunities! 