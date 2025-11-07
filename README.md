⭐ EZ Labs Contact Form

A responsive React single-page web application built as part of the EZ Labs Front-End Intern Test.
The app allows users to submit a contact form that integrates with a live API endpoint using Axios.

🚀 Tech Stack

⚛️ React.js — Frontend framework
🎨 TailwindCSS — Modern utility-first CSS
🌐 Axios — API integration
🧪 Postman — API testing
⚡ Vite / CRA — Development environment

🧩 Features

✅ Responsive design — works across mobile, tablet, and desktop
✅ Frontend validation (empty fields + valid email check)
✅ API integration with EZ Labs backend endpoint
✅ Displays “Form Submitted” message on success
✅ Light / Dark mode toggle
✅ Device view switch (Mobile / Tablet / iPad / Desktop)

🌐 API Information

Base URL:
https://vernanbackend.ezlab.in

Full Endpoint:
https://vernanbackend.ezlab.in/api/contact-us/

Method: POST

Headers:

Content-Type: application/json


Body Example (JSON):

{
  "name": "Rohan Hazra",
  "email": "rohannahzraoriginal6996@gmail.com",
  "phone": "9311263645",
  "message": "This is a test message from Postman"
}


Successful Response (Status: 201 Created):

{
  "message": "Contact request submitted and email sent successfully",
  "data": {
    "id": 960,
    "name": "Rohan Hazra",
    "email": "rohannahzraoriginal6996@gmail.com",
    "phone": "9311263645",
    "message": "This is a test message from Postman",
    "created_at": "2025-11-07T07:27:58.846923Z",
    "updated_at": "2025-11-07T07:27:58.846941Z"
  }
}

🧪 Postman Collection

📁 Postman dump file:
👉 EZ_Labs_Postman_Dump.json

Import this file into Postman to test the API directly.

🖥️ Local Setup Guide
1️⃣ Clone this repository
git clone https://github.com/RohanHazra/ezlabs-contact.git

2️⃣ Navigate into the project folder
cd ezlabs-contact

3️⃣ Install dependencies
npm install

4️⃣ Start the development server
npm start

5️⃣ Open in your browser
http://localhost:3000

📸 Preview

Desktop View:
A clean and responsive contact form featuring:

Name, Email, Phone, and Message fields

Live validation

Success message upon form submission

Toggleable light/dark theme

🧑‍💻 Author

Rohan Hazra
Front-End Developer | React.js Enthusiast
📧 rohannahzraoriginal6996@gmail.com

📂 Repository Info

🧪 Postman Dump: Included (EZ_Labs_Postman_Dump.json)

💻 Frontend: React + TailwindCSS

🌐 API: Integrated with live backend

🎯 Status: Completed and Tested




⭐ If you find this project helpful, don’t forget to star the repository!
