📬 Contact Form Website (Formspree Integration)

A responsive contact form website built using HTML & CSS, integrated with Formspree to handle form submissions without using a backend.
After successful submission, users are redirected to a Thank You page confirming that their message has been sent.

🌐 Live Demo

👉 (Add your GitHub Pages link here)
Example:

https://ankita292006.github.io/contact_form/

📁 Project Structure
project-folder/
│
├── index.html        # Main contact form page
├── thanks.html       # Thank you / confirmation page
├── style.css         # Styling for the website
├── assets/           # Images and icons
└── README.md         # Project documentation

✨ Features

📩 Contact form with Name, Email, and Message

🔗 Formspree integration (no backend required)

✅ Redirects to a confirmation page after submission

🎨 Clean and modern UI design

📱 Fully responsive layout

🛡️ Spam protection via Formspree

💯 Works on free Formspree plan

🛠️ Technologies Used

HTML5

CSS3

Formspree (for form handling)

⚙️ How Form Submission Works

User fills the contact form

On submit, data is sent to Formspree

Formspree emails the submission to the website owner

User is redirected to a Thank You page

Message displayed:
“Your message has been sent. We will contact you soon.”

ℹ️ Note: Auto-reply emails are not available in the Formspree free plan.

🧾 Formspree Setup

Create an account on https://formspree.io

Create a new form

Copy your Formspree form endpoint

Paste it in your <form> tag:

<form action="https://formspree.io/f/yourFormID" method="POST">


Add redirect input:

<input type="hidden" name="_redirect" value="thanks.html">

📸 Screenshots

(Optional — add screenshots of your form and thank-you page here)

🚀 How to Run Locally

Download or clone the repository

Open index.html in a browser

Fill the form and submit

You will be redirected to thanks.html

🧠 Limitations

❌ No automatic reply email (free Formspree plan)

❌ No backend/database

✔ Suitable for small websites and portfolios

📌 Future Enhancements

JavaScript form validation

Backend integration (Node.js / PHP)

Email auto-reply (paid plan)

Admin dashboard

👩‍💻 Author

Ankita G Negalur
📍 India

⭐ Acknowledgements

Formspree

GitHub Pages

📄 License

This project is open-source and available under the MIT License.# contact_form
contact form 
