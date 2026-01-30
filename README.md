# Amura

**Amura** is a modern event registration portal built to enhance student engagement and streamline event participation. The platform features an intuitive UI/UX and optimized performance, resulting in improved engagement and faster navigation for users. :contentReference[oaicite:1]{index=1}

🔗 **Live Demo:** https://amura-ten.vercel.app/ :contentReference[oaicite:2]{index=2}

## 🚀 Features

- 📝 **Event Registration Dashboard**
  - Browse and register for events seamlessly.
- 📲 **Responsive UI/UX**
  - Designed with responsiveness and usability in mind.
- 🚀 **High Performance**
  - Optimized navigation for faster page loads.
- ✉️ **Email Notifications**
  - Uses Nodemailer to send confirmation and update emails.
- 🔐 **Authentication & Database**
  - Supabase powers user data and session management.
- 💡 Built with React, Node.js & TypeScript for modern, type-safe development. :contentReference[oaicite:3]{index=3}

## 🧠 Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend | React + TypeScript |
| Backend | Node.js |
| Database | Supabase |
| Email | Nodemailer |
| Styling | Tailwind CSS |
| Deployment | Vercel |
| Package Manager | Bun / npm |

## 🛠️ Setup & Installation

Follow these steps to run the project locally:

### 1. Clone Repo
```bash
git clone https://github.com/Sumits-Cosmos/Amura.git
cd Amura
2. Install Dependencies

If using Bun (recommended):

bun install


Or with npm:

npm install

3. Create Environment Variables

Create a .env file and add:

# Supabase
VITE_SUPABASE_URL=your_supabase_url
VITE_SUPABASE_ANON_KEY=your_supabase_anon_key

# Email
EMAIL_HOST=smtp.yourmail.com
EMAIL_PORT=587
EMAIL_USER=your_email
EMAIL_PASS=your_email_password

# App
VITE_APP_BASE_URL=http://localhost:5173


Replace values with your real credentials.

4. Run Dev Server
bun dev


or

npm run dev


💡 Contributing

Fork the project

Create a feature branch (git checkout -b feature/xyz)

Commit your changes (git commit -m "feat: add xyz")

Push (git push origin feature/xyz)

Open a Pull Request

📝 License

Distributed under the MIT License.
