# ⚡ Meet Pokefriends!

Pokefriends is a fun way to take your photos and turn them into pokemon cards! 

This app was developed using Bolt.new as a project for ENTI 674 at the University of Calgary.
Contributors: Benjamin Teetzel, Ana Dragomir, Halie Ferguson, and Joshua Magcawas

This README was written by ChatGPT
---

## 🧠 Tech Stack

- ⚛️ React + TypeScript (.tsx)
- 🔥 Supabase (backend, auth, database)
- 🧪 Vite (build tool)
- 🧠 Bolt.new (AI-assisted coding)

---

## 🛠️ Setup Instructions

To run this project locally:

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/your-repo-name.git
cd your-repo-name
```
2. Install Dependencies
Make sure you have Node.js installed.

```bash
Copy code
npm install
```
3. Create a .env File
Create a .env file in the root folder and add the following:

env
Copy code
VITE_SUPABASE_URL=your-supabase-url
VITE_SUPABASE_ANON_KEY=your-supabase-anon-key
These keys are safe for frontend use but should not be committed. They're used to connect to your Supabase backend.

4. Run the Development Server
```bash
Copy code
npm run dev
Your app will be available at http://localhost:5173 (or the port shown in your terminal).
```
🗂️ Project Structure
```bash
Copy code
project/
├── .bolt/         # Bolt.new configuration (ignored in Git)
├── dist/          # Build output (ignored)
├── src/           # App source code (.tsx components, pages, logic)
├── supabase/      # Supabase database config and setup
├── public/        # Static assets
├── .env           # Environment variables (ignored)
├── .gitignore     # Files not tracked by Git
└── package.json   # Project dependencies and scripts
```
🌐 Deployment
This project can be deployed on:

Vercel

Netlify

Simply connect your GitHub repo and add your .env variables through the deployment dashboard.

🧾 Environment Variables

Variable	Description
VITE_SUPABASE_URL	Your Supabase project URL
VITE_SUPABASE_ANON_KEY	Public API key for frontend use

Do not commit the .env file. It’s already in .gitignore — you're good!

📄 License
This project is licensed under the MIT License — you’re free to use, modify, and share it.

👥 Contributing

Fork the repo

Clone it locally

Make your changes and commit

Open a pull request
