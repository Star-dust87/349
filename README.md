# Stella Kim - Portfolio Website

A professionally designed personal portfolio website showcasing my skills, projects, and professional experience.

## 🌟 Features

- **Responsive Design**: Fully optimized for all devices (desktop, tablet, mobile)
- **Modern UI**: Clean and professional layout with smooth animations and transitions
- **Multiple Pages**: Home, About, Projects, Skills, and Contact pages
- **Project Showcase**: Detailed project pages including my Mancala Game with AI
- **Skills Visualization**: Interactive display of technical and soft skills
- **Contact Form**: Functional contact form for sending messages
- **Accessibility**: Designed with web accessibility best practices in mind

## 🛠️ Technologies Used

- **HTML5**: Modern semantic markup
- **CSS3**: Custom styling with Flexbox and Grid for layouts
- **JavaScript**: Interactive elements and form validation
- **Font Awesome**: Icon library for visual elements
- **Google Fonts**: Typography enhancements

## 📂 Project Structure

```
portfolio-website/
│
├── index.html                  # Home page
├── about.html                  # About page
├── projects.html               # Projects listing page
├── skills.html                 # Skills page
├── contact.html                # Contact page
│
├── mancala-project.html        # Mancala Game project detail page
│
├── styles.css                  # Main stylesheet
├── script.js                   # Main JavaScript file
│
├── assets/                     # All static assets
│   ├── images/                 # Image files
│   │   ├── profile-image.jpg   # Professional photo
│   │   ├── about-photo.jpg     # Photo for about page
│   │   ├── mancala-banner.jpg  # Project banner images
│   │   └── ... (more project images)
│   │
│   ├── docs/                   # Documents
│   │   └── resume.pdf          # Downloadable resume
│   │
│   └── icons/                  # Custom icons (if not using Font Awesome)
```

## 📋 Pages Description

### Home Page
- Introduction with professional photo
- Brief bio and professional tagline
- Featured projects showcase
- Skills overview with visual indicators
- Call-to-action for contact

### About Page
- Detailed background information
- Education and experience timeline
- Personal interests and hobbies
- Downloadable resume

### Projects Page
- Project filtering by category
- Grid display of technical projects
- Mancala Game project highlight
- Portfolio website project

### Project Detail Pages
- Comprehensive project information
- Technologies used with visual tags
- Problem-solving approach
- Implementation details
- Screenshots and results

### Skills Page
- Tabbed interface for different skill categories
- Visual progress bars for skill proficiency
- Education details with course information
- Work experience timeline
- Languages and interests

### Contact Page
- Interactive contact form
- Direct email and phone contact options
- Social media links
- Location information

## 🚀 How to Run This Project

### Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/Star-dust87/349.git
   ```

2. **Navigate to the project directory**
   ```bash
   cd portfolio-website
   ```

3. **Open the project**
   - Simply open `index.html` in your preferred browser
   - For example: `firefox index.html` or double-click the file

4. **For development**
   - Use a live server extension for real-time updates
   - VS Code users can install the "Live Server" extension
   - Right-click on `index.html` and select "Open with Live Server"

### Hosting Options

This portfolio is designed to be easily deployed on:

1. **GitHub Pages** (recommended)
   - Push your repo to GitHub
   - Go to Settings > Pages
   - Select main branch
   - Your site will be published at `https://github.com/Star-dust87/349.git`

2. **Netlify**
   - Connect your GitHub repository
   - Netlify will automatically deploy your site
   - Free custom domain options available

3. **Vercel**
   - Import your GitHub repository
   - Automatic deployment and preview features

## 🎨 Customization

### Colors and Theme
The website uses a color scheme defined in CSS variables in the `:root` selector in `styles.css`. To change the color scheme, modify these variables:

```css
:root {
    --primary-color: #3498db;      /* Main accent color */
    --secondary-color: #2c3e50;    /* Secondary color */
    --accent-color: #e74c3c;       /* Highlight color */
    --light-color: #ecf0f1;        /* Background color */
    --dark-color: #2c3e50;         /* Text color */
    --text-color: #333;            /* Primary text color */
    --text-light: #737373;         /* Secondary text color */
}
```

### Typography
Fonts can be customized in the `body` selector in `styles.css`:

```css
body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    /* Change to your preferred font */
}
```

### Content
- Replace all instances of "Stella Kim" with your own name if using this as a template
- Update all placeholder text and images with your own content
- Modify project descriptions to reflect your actual work
- Update links to your GitHub, LinkedIn, and other profiles

## 📱 Responsive Design

The portfolio is fully responsive with specific breakpoints:
- **Desktop**: 992px and above
- **Tablet**: 768px to 991px
- **Mobile**: 767px and below

Media queries in `styles.css` handle these breakpoints automatically.

## 🔄 Future Enhancements

- [ ] Dark/Light mode toggle
- [ ] Blog section for technical articles
- [ ] Project filtering by technology
- [ ] Interactive skill timeline
- [ ] Multi-language support (English/Korean)

## 📞 Contact

Feel free to reach out if you have any questions or suggestions:

- **Email**: [Skim28@csu.fullerton.edu](mailto:Skim28@csu.fullerton.edu)
- **GitHub**: [Star_dust87](https://github.com/Star_dust87)

## 📜 License

This project is open source and available under the [MIT License](LICENSE).
