# 🔗 Links Manager

A modern, secure, and beautiful web application to organize and manage all your important links. Built with Next.js 15, NextAuth.js, Prisma, and shadcn/ui.

## ✨ Features

- 🔐 **Secure Authentication** - Google OAuth & Email/Password
- 📱 **Responsive Design** - Works on all devices
- 🌙 **Dark Mode Support** - Beautiful light and dark themes
- 🔗 **Link Management** - Add, edit, delete, and organize links
- 🎨 **Modern UI** - Built with shadcn/ui and Tailwind CSS
- ⚡ **Fast Performance** - Next.js 15 with Turbopack
- 🗄️ **Database** - PostgreSQL with Prisma ORM

## 🚀 Quick Start

### Prerequisites
- Node.js 18+ or Bun
- PostgreSQL database
- Google OAuth credentials (optional)

### Installation

1. **Clone the repository**
```bash
git clone https://github.com/akfverse/links-manager-app.git
cd links-manager-app
```

2. **Install dependencies**
```bash
npm install
# or
bun install
```

3. **Set up environment variables**
```bash
cp .env.example .env
```
Edit `.env` with your database and OAuth credentials.

4. **Set up database**
```bash
npx prisma migrate dev
npx prisma generate
```

5. **Start development server**
```bash
npm run dev
# or
bun dev
```

## 🌐 Deployment

### Vercel (Recommended)
1. Push your code to GitHub
2. Connect your repository to Vercel
3. Add environment variables
4. Deploy automatically

### Railway
1. Connect your GitHub repository
2. Add environment variables
3. Railway handles the rest

## 📄 License

This project is licensed under the MIT License.
