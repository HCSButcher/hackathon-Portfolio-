# Contact Form Website

This is a responsive contact form built using **pure HTML and CSS**, with form submission handled via **Formspree**. The site is deployed on **Netlify** and allows users to submit their information and messages directly to the site owner without using any JavaScript.

## 🚀 Features

- 📱 Fully responsive layout
- 🎨 Styled using modern vanilla CSS
- 📩 Integrated with [Formspree](https://formspree.io/) for email submissions
- ☁️ Hosted on [Netlify](https://www.netlify.com/)
- ✅ No JavaScript required / used

## 📂 Project Structure

project-root/
│
├── index.html # Main HTML file with form
├── style.css # Custom styles
└── README.md # Project description

## 📧 Form Functionality

Form submissions are handled through **Formspree** by specifying an `action` attribute in the `<form>` tag:

````html
<form action="https://formspree.io/f/your-form-id" method="POST"></form>

⚠️ Replace your-form-id with your actual Formspree form ID. 🌐 Deployment The
site is deployed on Netlify. Deployment steps: 1. Drag and drop the project
folder on Netlify Drop. 2. Or link your GitHub repository to Netlify and enable
automatic deployment. 3. No need to enable Netlify form handling
(data-netlify="true" is NOT used) since Formspree handles submissions.
📸Screenshot ✅ To Do Add success/thank-you page after form submission Add
accessibility improvements Add light/dark mode toggle (future) 📬 Contact For
any issues or inquiries, feel free to submit the form or email me directly at
trevor254oduol@email.com. ### ✅ To Use: 1. Replace: -`your-form-id` with your
Formspree form ID. -`https://your-live-site.netlify.app/` with your actual
Netlify live site link. - Add a screenshot as `screenshot.png` (optional). 2.
Save the file as `README.md`. 3. Push it to your GitHub repo: ```bash git add
README.md git commit -m "Add project README" git push
````
