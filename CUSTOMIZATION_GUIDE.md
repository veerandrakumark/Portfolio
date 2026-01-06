# 📝 Portfolio Customization Guide

## 🎯 Quick Edit Guide - All Lines You Need to Change

### 1. **PAGE TITLE** (Line 6)
```html
<title>Portfolio | Computer Science Student</title>
```
**Change to:** Your desired page title

---

### 2. **PROFILE IMAGE** (Lines 57 & 103)
```html
<!-- Line 57 - Hero Section -->
<img src="assets/images/profile.jpg" alt="Profile" class="hero-profile-image" id="heroProfileImage">

<!-- Line 103 - About Section -->
<img src="assets/images/profile.jpg" alt="Profile" class="about-profile-image" id="aboutProfileImage">
```
**Action:** Place your profile photo at `assets/images/profile.jpg` (square image, min 500x500px)

---

### 3. **YOUR NAME** (Line 64)
```html
<span class="name-main">Your Name</span>
```
**Change to:** Your actual name

---

### 4. **HERO TAGLINE** (Line 67)
```html
<p class="hero-tagline">
    Computer Science Student | Front-End Developer | AI Enthusiast
</p>
```
**Change to:** Your personal tagline (e.g., "Software Engineer | Full-Stack Developer | Tech Enthusiast")

---

### 5. **ABOUT SECTION - WHO I AM** (Lines 117-121)
```html
<p>
    Passionate Computer Science student with a strong foundation in web development and 
    emerging technologies. I thrive on creating elegant, user-centric digital experiences 
    that blend creativity with technical excellence.
</p>
```
**Change to:** Your personal bio

---

### 6. **ABOUT SECTION - WHAT I DO** (Lines 130-134)
```html
<p>
    Specialized in front-end development with expertise in HTML, CSS, and JavaScript. 
    I'm deeply interested in AI, automation, and modern web experiences that push 
    the boundaries of what's possible in the browser.
</p>
```
**Change to:** Your skills and interests

---

### 7. **ABOUT SECTION - MY VISION** (Lines 145-149)
```html
<p>
    To bridge the gap between cutting-edge technology and intuitive design, creating 
    solutions that are not only functional but also delightful to use. I believe in 
    continuous learning and staying ahead of the curve in this ever-evolving field.
</p>
```
**Change to:** Your vision/goals

---

### 8. **SKILLS SECTION** (Lines 165-253)

#### Frontend Skills (Lines 165-190)
```html
<!-- Line 165-166 -->
<span class="skill-name">HTML</span>
<span class="skill-percent">95%</span>
<!-- Line 169 -->
<div class="skill-progress" data-progress="95"></div>

<!-- Line 174-175 -->
<span class="skill-name">CSS</span>
<span class="skill-percent">90%</span>
<!-- Line 178 -->
<div class="skill-progress" data-progress="90"></div>

<!-- Line 183-184 -->
<span class="skill-name">JavaScript</span>
<span class="skill-percent">85%</span>
<!-- Line 187 -->
<div class="skill-progress" data-progress="85"></div>
```
**Change to:** Your skills and percentages (update both the text AND data-progress attribute)

#### Programming Skills (Lines 197-221)
```html
<!-- Similar structure - update skill names and percentages -->
```

#### Tools Skills (Lines 229-253)
```html
<!-- Similar structure - update skill names and percentages -->
```

---

### 9. **PROJECTS SECTION** (Lines 265-330)

#### Project 1 (Lines 276-285)
```html
<!-- Line 276 -->
<h3 class="project-title">Project Title 1</h3>
<!-- Lines 277-280 -->
<p class="project-description">
    A modern web application showcasing advanced front-end techniques and 
    interactive user experiences.
</p>
<!-- Lines 269-271 - Tech Stack -->
<span>HTML</span>
<span>CSS</span>
<span>JavaScript</span>
<!-- Lines 282-283 - Links -->
<a href="#" class="btn btn-small btn-primary">Live Demo</a>
<a href="#" class="btn btn-small btn-secondary">GitHub</a>
```
**Change to:** Your project details, tech stack, and links

#### Project 2 (Lines 298-307)
**Same structure - update with your second project**

#### Project 3 (Lines 320-329)
**Same structure - update with your third project**

---

### 10. **EDUCATION SECTION** (Lines 343-350)
```html
<!-- Line 343 -->
<div class="timeline-year">2021 - Present</div>
<!-- Line 344 -->
<h3 class="timeline-title">B.Tech – Computer Science & Business Systems</h3>
<!-- Line 345 -->
<p class="timeline-institution">Your University Name</p>
<!-- Lines 346-350 -->
<p class="timeline-description">
    Pursuing a comprehensive degree combining computer science fundamentals 
    with business systems knowledge, focusing on modern software development 
    and emerging technologies.
</p>
```
**Change to:** Your education details

---

### 11. **ACHIEVEMENTS SECTION** (Lines 368-394)

#### Hackathons (Lines 368-369)
```html
<h3>Hackathons</h3>
<p>Participated in multiple hackathons, showcasing problem-solving skills and innovative thinking.</p>
```
**Change to:** Your hackathon achievements

#### Paper Presentations (Lines 381-382)
```html
<h3>Paper Presentations</h3>
<p>Presented research papers on emerging technologies and their applications in modern computing.</p>
```
**Change to:** Your paper presentation details

#### Certifications (Lines 393-394)
```html
<h3>Certifications</h3>
<p>Earned certifications in web development, programming languages, and modern development tools.</p>
```
**Change to:** Your certifications

---

### 12. **RESUME DOWNLOAD** (Line 415)
```html
<a href="assets/resume.pdf" download class="btn btn-primary btn-large">
```
**Action:** Place your resume PDF at `assets/resume.pdf`

---

### 13. **SOCIAL LINKS** (Lines 436-456)

#### GitHub (Line 436)
```html
<a href="https://github.com" target="_blank" class="social-link">
```
**Change to:** Your GitHub profile URL

#### LinkedIn (Line 442)
```html
<a href="https://linkedin.com" target="_blank" class="social-link">
```
**Change to:** Your LinkedIn profile URL

#### Email (Line 450)
```html
<a href="mailto:your.email@example.com" class="social-link">
```
**Change to:** Your email address

---

### 14. **FOOTER** (Line 487)
```html
<p>&copy; 2024 Portfolio. All rights reserved.</p>
```
**Change to:** Your copyright text (optional)

---

## 📋 Summary Checklist

- [ ] Page title (Line 6)
- [ ] Profile image path (Lines 57, 103) - Add image to `assets/images/profile.jpg`
- [ ] Your name (Line 64)
- [ ] Hero tagline (Line 67)
- [ ] About section - Who I Am (Lines 117-121)
- [ ] About section - What I Do (Lines 130-134)
- [ ] About section - My Vision (Lines 145-149)
- [ ] Skills - Frontend (Lines 165-190)
- [ ] Skills - Programming (Lines 197-221)
- [ ] Skills - Tools (Lines 229-253)
- [ ] Projects - Project 1 (Lines 276-285)
- [ ] Projects - Project 2 (Lines 298-307)
- [ ] Projects - Project 3 (Lines 320-329)
- [ ] Education (Lines 343-350)
- [ ] Achievements (Lines 368-394)
- [ ] Resume PDF (Line 415) - Add file to `assets/resume.pdf`
- [ ] GitHub link (Line 436)
- [ ] LinkedIn link (Line 442)
- [ ] Email address (Line 450)
- [ ] Footer copyright (Line 487)

---

## 💡 Tips

1. **Keep the HTML structure** - Only change the text content, not the HTML tags
2. **Match percentages** - When updating skills, make sure the text percentage matches the `data-progress` attribute
3. **Image format** - Use JPG or PNG for profile images (square format recommended)
4. **Links** - Make sure all your project and social links are valid URLs
5. **Test** - After making changes, test the website in a browser to ensure everything displays correctly
