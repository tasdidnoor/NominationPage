# Election Nomination Page

A simple, mobile-responsive webpage for collecting student nominations.

## Setup Instructions

1. **Get a Formspree ID:**
   - Go to [Formspree](https://formspree.io/) and create a free account.
   - Create a new project and a new form.
   - Copy the unique form ID provided (it looks like `mjvnyvlk`).

2. **Update index.html:**
   - Open `index.html`.
   - Find the `<form>` tag: `<form action="https://formspree.io/f/your-form-id" method="POST">`.
   - Replace `your-form-id` with your actual ID.

3. **Deploy:**
   - You can host this for free using **GitHub Pages**.
   - Go to your repository settings on GitHub -> Pages -> Select the `main` branch and `/root` folder -> Save.

## Features
- Minimalist, high-contrast design.
- Mobile-responsive.
- No client-side email format validation (as requested).
- Direct-to-email submissions via Formspree.
