# OMEGA-S-CHOREOGRAPHY# Omega's Choreography — Website Development Report
#Student information
Student name:Omega Songeya
Student ID: 2412259330
Github repostory:

## Question 2: HTML Elements

### 1. Five challenging elements
- **`<form>`** – Building the join form with multiple input types and labels required careful validation.  
- **`<table>`** – Structuring the “Shows & Events” table with headers and `<time>` tags was complex.  
- **`<video>`** – Embedding the video reel with controls and ensuring playback compatibility.  
- **`<figure>` & `<figcaption>`** – Combining images with captions for bookings demanded semantic accuracy.  
- **`<nav>`** – Implementing navigation with accessibility attributes (`role`, `aria-label`) added difficulty.

### 2. Use of semantic elements
- **`<header>`** – Contained site title and navigation.  
- **`<section>`** – Divided content into About, Shows, Media, and Join sections.  
- **`<article>`** – Used for mission statement and video reel content.  
- **`<footer>`** – Provided contact information and email link.

### 3. Most useful element for layout
- **`<section>`** – Organized the site into clear thematic blocks, making the structure easy to follow.

---

## Question 3: HTML Attributes

### 1. Three essential attributes
- **`src`** – Used in `<img>` and `<video>` to embed media.  
- **`href`** – Used in `<a>` for navigation and social links.  
- **`datetime`** – Used in `<time>` for machine-readable event dates.

### 2. Difference between class and id
- **`class`** – Applied to reusable styling groups (e.g., `class="lead"`, `class="profile-image"`).  
- **`id`** – Used for unique identifiers (e.g., `id="about"`, `id="join-form"`) to target specific sections.

### 3. Attribute that improved user experience most
- **`placeholder`** – Guided users in form inputs, improving usability of the join form.

---

## Question 4: Development Process

### 1. Planning structure
- Outlined main sections: About, Shows, Media, Join.  
- Selected semantic tags for clarity and accessibility.

### 2. Testing and debugging
- Previewed in browser after each change.  
- Checked form inputs, video playback, and table rendering.  
- Used developer tools to inspect element nesting.

### 3. Challenges and solutions
- Accessibility attributes (`role`, `aria-label`) were initially confusing → solved with documentation.  
- Image sizing issues due to incorrect `title` attribute → corrected with CSS.  
- Ensuring semantic correctness → validated against HTML5 guidelines.

---

## Question 5: Git & GitHub Implementation

### 1. Git commands used
- `git init` – Initialized repository.  
- `git add .` – Staged changes.  
- `git commit -m "message"` – Committed changes.  
- `git push origin main` – Pushed to GitHub.

### 2. Commit strategy
- Around 10 commits.  
- Messages were descriptive, e.g., “Added join form,” “Embedded video reel,” “Fixed table dates.”

### 3. Importance of version control
- Tracks changes, prevents data loss, enables collaboration, and allows rollback if errors occur.

---

## Question 6: Code Quality & Best Practices

### 1. Ensuring valid HTML
- Used W3C Validator to check for errors.  
- Fixed issues like incorrect attribute usage (`title` instead of `style` for image dimensions).

### 2. Best practices followed
- Consistent indentation.  
- Semantic tags for structure.  
- Accessibility attributes (`role`, `aria-label`).  
- Comments for clarity.

### 3. Improvements with more time
- Add CSS for styling and responsive design.  
- Improve accessibility with ARIA roles.  
- Expand navigation menu and add more interactive content.

---
