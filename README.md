# my-portfolio
# Kevin Nizeyimana - Professional Resume Website

![Resume Screenshot](https://raw.githubusercontent.com/k-nizy/pictures-/main/kevin%20passaport.jpg)  
*A modern, responsive resume website built with HTML, CSS, and JavaScript*

# 🌟 Features
 **Fully Responsive** - Works on mobile, tablet, and desktop
- **Interactive Elements**:
  - Smooth scrolling navigation
  - Animated skill bars
  - Contact form with validation
  - Dark/light mode toggle
- **Professional Sections**:
  - About me
  - Skills with progress indicators
  - Education & experience timeline
  - Project portfolio
  - Contact information

# 🛠️ Technologies Used
- **Frontend**: HTML5, CSS3, JavaScript
- **Hosting**: GitHub Pages
- **Design**: Custom CSS (no frameworks)

# 🚀 How to Deploy
1. **Fork this repository**
2. **Enable GitHub Pages**:
   - Go to Settings → Pages
   - Select `main` branch and `/ (root)` folder
   - Save (your site will deploy to `https://<username>.github.io/resume-website`)

# 🔧 Customization Guide
# Replace Images
1. Profile picture: Replace `kevin-profile.jpg`
2. Project images: Replace `project1.jpg`, `project2.jpg`, `project3.jpg`

 Update Content
Edit these sections in `index.html`:
```html
<!-- About Section -->
<section id="about">...</section>

<!-- Skills Section -->
<section id="skills">...</section>

<!-- Projects Section -->
<section id="projects">...</section>


How It Works
Key JavaScript Functions
Mobile Navigation

hamburger.addEventListener('click', () => {
  navMenu.classList.toggle('active');
});


Form Validation:

contactForm.addEventListener('submit', function(e) {
  // Validates name, email, and message fields
});

Dark Mode Toggle:


darkModeToggle.addEventListener('click', () => {
  document.body.classList.toggle('dark-mode');
});
 
🌐 Live Demo
View the live website

https://k-nizy.github.io/my-portfolio/

 Key Elements Included:
1. **Visual Preview** - Uses your GitHub-hosted profile picture
2. **Deployment Instructions** - Simple steps for GitHub Pages
3. **Customization Guide** - Where to edit content/images
4. **Technical Breakdown** - Explains key JavaScript functions
5. **Live Demo Link** - Direct link to your hosted resume

 How to Use This README:
1. Copy this entire text
2. Create a new file named `README.md` in your project folder
3. Paste the content
4. Customize the links and details as needed
