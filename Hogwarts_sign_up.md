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

![image](https://github.com/user-attachments/assets/1f61e97a-6d65-47ad-bbfa-8a2e4a8e057b)


---

### 2. Install Elementor

1. In the WordPress dashboard, go to **Plugins → Add New**.
![image](https://github.com/user-attachments/assets/113a2206-8bc1-40c6-aa2e-751b8f441eac)

3. Search for **Elementor Website Builder**.
![image](https://github.com/user-attachments/assets/a7d696bb-f6f8-4f37-8acd-47408b8ad1d4)

5. Click **Install** and then **Activate**.

---

### 3. Create the Google Form

- Go to [Google Forms](https://forms.google.com) and create a new form titled:
  **"Hogwarts School of Witchcraft and Wizardry – Student Admission Form"**

- Add the following magical fields:
  1. **Name** (Short Answer): _“What name shall appear on your Hogwarts acceptance letter?”_
  2. **Email Address** (Short Answer): _“Where can we send your owl with the acceptance letter?”_
  3. **Dropdown** – _“Choose Your House”_:
     - Gryffindor
     - Ravenclaw
     - Hufflepuff
     - Slytherin
  4. **Paragraph** – _“Why do you want to join Hogwarts?”_
  5. **Checkbox** – _“I solemnly swear that I am up to no good and I accept the Hogwarts Code of Conduct.”_

- Customize the theme:
  - Use mystical colors (deep purple, midnight blue)
  - Add a magical background (e.g., stars, parchment)
  - Choose a decorative font
    
- Click **Send → Embed (< >)** → Copy the HTML embed code.

---

### 4. Build the Page with Elementor

1. In WordPress, go to **Pages → Add New** → Title it: `Hogwarts Sign-Up`
![image](https://github.com/user-attachments/assets/2c2d16a2-ff13-436a-a6cd-e79811de36e3)

3. Click **Edit with Elementor**
![image](https://github.com/user-attachments/assets/3fcb05bf-be05-48b8-906d-e672f16fe43a)

5. Add the following widgets:
   - **Heading**: `Welcome to Hogwarts`
   - **Text Editor**: Add a magical intro
   - **HTML**: Paste your Google Form embed code here
6. Style the page:
   - Add a background image (e.g., Hogwarts castle, night sky)
   - Use magical fonts (like Cormorant, Cinzel)
   - Set house-themed button colors
7. Click **Publish** when you're happy with the design.

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
