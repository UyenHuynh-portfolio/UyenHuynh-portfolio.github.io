# Uyen Huynh - Marketing Operations Portfolio

## How to Edit Your Portfolio

### 1. **Basic Text Changes**
To update any text content:
- Open `index.html` in any text editor (Notepad++, VS Code, or even basic Notepad)
- Use Ctrl+F to find the text you want to change
- Replace with your new content
- Save the file

### 2. **Adding Images/Videos**
To add your event photos and videos:

**For Images:**
\`\`\`html
<!-- Replace this placeholder: -->
<div class="media-placeholder">
    📸 [SPACE FOR EVENT PHOTOS/VIDEOS]
</div>

<!-- With actual images: -->
<div class="project-images">
    <img src="images/event1.jpg" alt="NFQ Summit 2024" style="width: 100%; border-radius: 12px; margin-bottom: 1rem;">
    <img src="images/event2.jpg" alt="Team coordination" style="width: 100%; border-radius: 12px;">
</div>
\`\`\`

**For Videos:**
\`\`\`html
<video controls style="width: 100%; border-radius: 12px;">
    <source src="videos/event-highlights.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>
\`\`\`

### 3. **Updating Project Results**
To change the numbers in result boxes:
\`\`\`html
<div class="result-item">
    <span class="result-number">400+</span>  <!-- Change this number -->
    <span class="result-text">Attendees Managed</span>  <!-- Change this text -->
</div>
\`\`\`

### 4. **Adding New Projects**
Copy the entire project card structure and modify:
\`\`\`html
<div class="project-card">
    <div class="project-header">
        <h3>Your New Project Title</h3>
        <p>Project Subtitle</p>
    </div>
    <div class="project-content">
        <!-- Add your content here -->
    </div>
</div>
\`\`\`

### 5. **Changing Colors**
Main colors are defined at the top. To change the accent color from orange:
- Find `#F59E0B` and `#FBBF24` in the CSS
- Replace with your preferred colors (use a color picker tool)

### 6. **Contact Information**
Update your contact details in multiple places:
- Hero section contact info
- Contact section details
- Email links

### 7. **File Structure**
Create this folder structure:
\`\`\`
portfolio/
├── index.html (your main file)
├── images/
│   ├── event1.jpg
│   ├── event2.jpg
│   └── profile.jpg
└── videos/
    └── event-highlights.mp4
\`\`\`

### 8. **Publishing Options**

**Option 1: GitHub Pages (Free)**
1. Create GitHub account
2. Create new repository named "portfolio"
3. Upload your files
4. Go to Settings > Pages
5. Select "Deploy from branch" > "main"
6. Your site will be at: username.github.io/portfolio

**Option 2: Netlify (Free)**
1. Go to netlify.com
2. Drag and drop your portfolio folder
3. Get instant live URL

**Option 3: Local Hosting**
- Just double-click `index.html` to open in browser
- Share the file directly with employers

### 9. **Quick Customization Tips**

**Change your hero emoji:**
\`\`\`html
<div class="hero-image">
    🚀  <!-- Change this to any emoji -->
</div>
\`\`\`

**Update progress percentage:**
\`\`\`css
.progress-fill {
    width: 75%;  /* Change this percentage */
}
\`\`\`

**Add new competency:**
\`\`\`html
<div class="competency-card">
    <h3>🎯 YOUR NEW SKILL CATEGORY</h3>
    <ul>
        <li>Skill 1</li>
        <li>Skill 2</li>
    </ul>
</div>
\`\`\`

### 10. **Mobile Responsiveness**
The portfolio is already mobile-friendly, but test on different devices:
- Use browser developer tools (F12)
- Select different device sizes
- Adjust if needed

### Need Help?
- For basic edits: Use any text editor
- For advanced changes: Consider learning basic HTML/CSS
- For professional help: Hire a web developer for complex modifications

The portfolio is designed to be easily editable while maintaining professional appearance!
