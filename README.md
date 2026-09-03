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

Row Level Security (RLS) is enabled on the Supabase prayers table.

Never expose a Supabase service_role key or other secret credentials in frontend code or GitHub.

🚀 Getting Started

Clone the Repository

git clone https://github.com/yelportillo/bible-app.git
cd bible-app

Run Locally

The project doesn’t require a build system. You can open index.html directly in your browser.

Alternatively, run a local web server:

python3 -m http.server 8000

Then open:

http://localhost:8000

⚙️ Supabase

The app uses Supabase to store prayers submitted to the Prayer Wall.

Your Supabase project should have:

* A prayers table
* Row Level Security enabled
* Appropriate policies for reading, inserting, updating, and deleting prayers

📁 Project Structure

bible-app/
├── index.html
└── README.md

🙏 Purpose

The goal of this project is to create a simple space where people can read Scripture, reflect through prayer, and encourage others through a shared Prayer Wall.

⸻

GitHub: https://github.com/yelportillo/bible-app
