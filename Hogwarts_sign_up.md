#  Hogwarts Sign-Up Form (Elementor + Google Forms)

A magical website built with WordPress and Elementor, featuring a Hogwarts sign-up form embedded from Google Forms — all hosted locally using LocalWP.

---

##  Project Overview

This project creates an interactive and visually magical Hogwarts sign-up page using **Elementor** for design and **Google Forms** for the actual sign-up form. Everything is hosted **locally** on your computer using **LocalWP**.

---

##  Tools Used

- **LocalWP** – Local WordPress hosting
- **WordPress** – Content Management System
- **Elementor** – Drag-and-drop website builder plugin
- **Google Forms** – Free form creation and submission handling

---

##  How to Build This

### 1. Set Up WordPress with LocalWP

1. Download and install [LocalWP](https://localwp.com).
2. Open LocalWP and click **“+ Create a New Site”**.
3. Name your site: `hogwarts-signup.local`.
4. Choose “Preferred” settings and finish the setup.
5. Once done, click **“WP Admin”** to open your local WordPress Dashboard.

---

### 2. Install Elementor

1. In the WordPress dashboard, go to **Plugins → Add New**.
2. Search for **Elementor Website Builder**.
3. Click **Install** and then **Activate**.

---

### 3. Create the Google Form

1. Go to [Google Forms](https://forms.google.com) → Create a new form.
2. Title: `Hogwarts Sign-Up Form`
3. Add the following fields:
   - Name (Short Answer)
   - Email
   - Dropdown: Choose Your House (Gryffindor, Ravenclaw, Hufflepuff, Slytherin)
   - Paragraph: Why do you want to join Hogwarts?
   - Checkbox: Accept Hogwarts Code of Conduct
4. Customize form appearance (colors, fonts).
5. Click **Send → Embed (< >)** → Copy the iframe embed code.

---

### 4. Build the Page with Elementor

1. In WordPress, go to **Pages → Add New** → Title it: `Hogwarts Sign-Up`
2. Click **Edit with Elementor**
3. Add the following widgets:
   - **Heading**: `Welcome to Hogwarts`
   - **Text Editor**: Add a magical intro
   - **HTML**: Paste your Google Form embed code here
4. Style the page:
   - Add a background image (e.g., Hogwarts castle, night sky)
   - Use magical fonts (like Cormorant, Cinzel)
   - Set house-themed button colors
5. Click **Publish** when you're happy with the design.

---

##  Testing

1. Open your local site at: `http://hogwarts-signup.local/hogwarts-sign-up`
2. Fill out the form and submit
3. Check responses inside Google Forms → Responses tab

---

##  Optional 

- Use Elementor’s **Icon Box** widget to show each house logo with animations.
- Add hover effects or transitions for an interactive experience.
- Add sound effects using HTML:  
  ```html
  <audio autoplay loop>
    <source src="your-magical-sound.mp3" type="audio/mpeg">
  </audio>
