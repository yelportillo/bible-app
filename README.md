📖 Bible App

A modern, responsive Bible web app designed to encourage daily Scripture reading and prayer.

✨ Features

* 📖 Verse of the Day — Display a randomly selected Bible verse.
* 🙏 Scripture-Inspired Prayers — Generate a prayer based on the displayed verse.
* 🧱 Prayer Wall — Share prayers with the community.
* ✏️ Edit Prayers — Edit prayers you’ve submitted.
* 🗑️ Delete Prayers — Remove your own prayers.
* 👤 Anonymous Posting — Names are optional.
* ☁️ Supabase Integration — Store prayers in a cloud database.
* 💾 LocalStorage Fallback — Continue using the app if Supabase isn’t available.
* 📱 Responsive Design — Works across desktop and mobile devices.
* 🌌 Modern UI — Dark blue glassmorphism-inspired interface.

🛠️ Built With

* HTML5
* CSS3
* JavaScript
* Supabase
* LocalStorage
* Google Fonts — Inter

🔐 Security

The application uses a Supabase publishable key for frontend database access.

Row Level Security (RLS) should be enabled on the Supabase prayers table to control database access.

Never expose a Supabase service_role key or other secret credentials in frontend code or GitHub.

🚀 Getting Started

1. Clone the repository

git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
cd YOUR-REPOSITORY

2. Open the app

This project does not require a build system.

You can open index.html directly in your browser, or serve it with a local web server:

python3 -m http.server 8000

Then visit:

http://localhost:8000

⚙️ Supabase

The app connects to Supabase using the JavaScript client.

Make sure your Supabase project has:

* A prayers table
* Row Level Security enabled
* Appropriate policies for reading, creating, updating, and deleting prayers

📁 Project Structure

.
├── index.html
└── README.md

🙏 Purpose

The goal of this project is to create a simple space where people can read Scripture, reflect through prayer, and encourage others through a shared prayer wall.

📜 License

This project is open source. Add your preferred license here, such as the MIT License.
