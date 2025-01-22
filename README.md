# 📚 University Library Management System

A modern, full-stack library management system built with Next.js 15, TypeScript, and PostgreSQL. This system provides a seamless experience for both students and administrators to manage library resources efficiently.

## 🛠️ Technologies Used

- **Frontend**

  - Next.js 15
  - TypeScript
  - Tailwind CSS
  - ShadCN UI Components
  - React Hook Form
  - Zod Validation

- **Backend**
  - PostgreSQL with Neon
  - Drizzle ORM
  - NextAuth.js
  - Upstash Redis
  - ImageKit for media
  - Resend for emails

## ✨ Key Features

### For Students

- **Authentication & Profile**

  - Email-based authentication
  - University ID verification
  - Profile management
  - Activity tracking

- **Book Management**

  - Browse available books
  - Advanced search & filtering
  - Book details with 3D cover effects
  - Video previews
  - Real-time availability tracking

- **Borrowing System**
  - One-click book borrowing
  - Automated due date reminders
  - Digital receipts
  - Return tracking
  - Borrowing history

### For Administrators

- **Dashboard**

  - Real-time statistics
  - User activity monitoring
  - Book inventory tracking
  - Borrowing analytics

- **User Management**

  - Account approval system
  - Role management
  - Activity monitoring
  - Bulk user actions

- **Book Management**

  - Add/Edit books
  - Manage inventory
  - Track borrowing history
  - Generate reports

- **Advanced Features**
  - Rate limiting
  - DDoS protection
  - Caching system
  - Email notifications
  - PDF receipt generation

## 🚀 Getting Started

1. **Clone the repository**

bash
git clone https://github.com/your-username/university-library.git
cd university-library

2. **Install dependencies**

bash
npm install

3. **Set up environment variables**
   Create a `.env.local` file with:

env
NEXT_PUBLIC_IMAGEKIT_PUBLIC_KEY=
IMAGEKIT_PRIVATE_KEY=
NEXT_PUBLIC_IMAGEKIT_URL_ENDPOINT=
DATABASE_URL=
UPSTASH_REDIS_URL=
UPSTASH_REDIS_TOKEN=
AUTH_SECRET=
RESEND_TOKEN=

4. **Run migrations**

bash
npm run db:migrate

5. **Start development server**

bash
npm run dev

## 📦 Project Structure

university-library/
├── app/
│ ├── (auth)/
│ ├── (root)/
│ └── admin/
├── components/
│ ├── ui/
│ └── admin/
├── database/
│ ├── migrations/
│ └── schema.ts
├── lib/
│ └── validations/
└── public/

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- Next.js team for the amazing framework
- Vercel for hosting
- Neon for PostgreSQL database
- Upstash for Redis services
- ImageKit for media management
