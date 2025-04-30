#  Hogwarts Sign-Up Form (Elementor + Google Forms)

A magical sign-up website inspired by the Hogwarts School of Witchcraft and Wizardry — built using WordPress, Elementor, and Google Forms. Hosted locally using LocalWP for quick and easy development.

---

## Project Overview

This project creates a whimsical and interactive sign-up page where aspiring witches and wizards can enroll at Hogwarts. It utilizes:
- **Elementor** for visual page design (no coding needed!)
- **Google Forms** for form handling
- **LocalWP** for local WordPress hosting


---

## Tools Used

- [LocalWP](https://localwp.com/) – for local WordPress environment
- [Elementor](https://elementor.com/) – for drag-and-drop website design
- [Google Forms](https://forms.google.com) – to build and manage the sign-up form

---

## 🛠️ How to Build This

### 1. Set Up WordPress Locally
- Download and install **LocalWP**
- Create a new site (e.g., `hogwarts-signup.local`)
- Open the WordPress Admin Dashboard from LocalWP

### 2. Install Elementor Plugin
- Go to `Plugins → Add New` in your WP Dashboard
- Search for **Elementor Website Builder**
- Click **Install** and then **Activate**

### 3. Create the Google Form
- Visit [Google Forms](https://forms.google.com)
- Create a new form with the following fields:
  - **Name** (Short Answer)
  - **Email**
  - **Dropdown**: Choose Your House (Gryffindor, Ravenclaw, Hufflepuff, Slytherin)
  - **Paragraph**: Why do you want to join Hogwarts?
  - **Checkbox**: Accept Hogwarts Code of Conduct
- Customize form colors and fonts to match your Hogwarts theme
- Click **Send → Embed (`< >`)** → Copy the embed HTML code

### 4. Build the Page in Elementor
- Go to `Pages → Add New` → Title: **Hogwarts Sign-Up**
- Click **Edit with Elementor**
- Add the following widgets:
  - **Heading**: “Welcome to Hogwarts”
  - **Text Editor**: Short magical description
  - **HTML**: Paste the embed code from Google Forms
- Style your page:
  - Set a magical background (e.g., Hogwarts castle, night sky)
  - Use magical fonts like **Cinzel**, **Cormorant**, or **IM Fell English**
  - Customize form section colors to represent the Hogwarts houses
- Click **Publish**

---

## Testing

- Open the page at `hogwarts-signup.local/hogwarts-sign-up`
- Fill out the form and submit
- Check the linked Google Form to view responses

---

## Optional 

- Add house icons and animations using **Elementor Icon Box**
- Use hover effects or entrance animations for elements
- Embed background music using the **HTML** widget:
  ```html
  <audio autoplay loop>
    <source src="your-music-file.mp3" type="audio/mpeg">
  </audio>
