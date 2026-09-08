# 🤖 Creator AI – AI-Powered Content Generator

**Creator AI** is an AI-powered content generation platform that helps users create high-quality content quickly and efficiently using **Google Gemini AI**.

It provides a modern, responsive, and user-friendly interface with features such as AI content generation, multiple content templates, secure authentication, content history, usage tracking, subscription management, and database integration.

## 🌐 Live Demo

🚀 **Live Project:** https://content-generator-liard.vercel.app/

## ✨ Features

* 🤖 **AI-Powered Content Generation**
  Generate high-quality content using the Google Gemini API.

* 📝 **Multiple Content Templates**
  Choose from predefined templates for different content-generation requirements.

* 🔐 **Secure Authentication**
  User authentication and account management powered by Clerk.

* 📚 **Content History**
  Save and access previously generated content.

* 📋 **Copy Generated Content**
  Easily copy generated content for further use.

* 📊 **Usage Tracking**
  Track AI credit usage and monitor generation limits.

* 💳 **Subscription & Billing**
  Manage subscriptions and credit-based usage.

* 🎨 **Modern & Responsive UI**
  Clean, responsive, and user-friendly interface built with Tailwind CSS.

* 🗄️ **Database Integration**
  PostgreSQL database integration using Drizzle ORM.

## 🛠️ Tech Stack

| Technology            | Purpose                              |
| --------------------- | ------------------------------------ |
| **Next.js**           | Full-stack React framework           |
| **React.js**          | User interface                       |
| **TypeScript**        | Type-safe development                |
| **Tailwind CSS**      | Styling and responsive design        |
| **Clerk**             | Authentication and user management   |
| **Google Gemini API** | AI content generation                |
| **PostgreSQL**        | Database                             |
| **Drizzle ORM**       | Database management                  |
| **Razorpay**          | Subscription and payment integration |

## 📂 Project Structure

```text
Creator-AI/
├── app/
│   ├── (auth)/
│   ├── (context)/
│   ├── (data)/
│   ├── api/
│   ├── dashboard/
│   ├── globals.css
│   ├── layout.tsx
│   └── page.tsx
│
├── components/
│   └── ui/
│
├── lib/
│
├── utils/
│   ├── AiModal.tsx
│   ├── db.tsx
│   └── schema.tsx
│
├── middleware.ts
├── drizzle.config.js
├── next.config.mjs
├── package.json
├── tailwind.config.ts
└── tsconfig.json
```

## ⚙️ Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/ankitkgupta11-g/AI-Powered-Content-Generator-.git
```

### 2. Navigate to the Project

```bash
cd AI-Powered-Content-Generator-
```

### 3. Install Dependencies

```bash
npm install
```

### 4. Configure Environment Variables

Create a `.env.local` file in the root directory and add the required environment variables:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
DATABASE_URL=your_postgresql_database_url
GEMINI_API_KEY=your_gemini_api_key
```

If Razorpay is configured in the project, add the required Razorpay environment variables as well.

> ⚠️ **Important:** Never commit `.env.local`, API keys, secret keys, passwords, or other sensitive credentials to GitHub.

### 5. Start the Development Server

```bash
npm run dev
```

Open your browser and visit:

```text
http://localhost:3000
```

## 🔄 How It Works

```text
User
  ↓
Select Content Template
  ↓
Enter Required Information
  ↓
Generate Content
  ↓
Google Gemini API
  ↓
AI Generated Content
  ↓
Display / Copy / Save Content
```

## 🚀 Deployment

The project is deployed using **Vercel**.

🔗 **Live Application:**
https://content-generator-liard.vercel.app/

To deploy your own version:

1. Fork or clone this repository.
2. Push the project to GitHub.
3. Import the repository into Vercel.
4. Configure the required environment variables.
5. Deploy the application.

## 🔮 Future Enhancements

* 🤖 Support for additional AI models
* 📝 More content-generation templates
* 📊 Advanced content analytics
* 💡 AI-powered content suggestions
* 👥 Team collaboration features
* 🎯 Improved content customization
* 📄 Export generated content in different formats
* 💳 Enhanced subscription plans

## 🤝 Contributing

Contributions are welcome and appreciated.

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Commit your changes.
5. Push your branch.
6. Open a Pull Request.

## 📄 License

This project is licensed under the **MIT License**.

## 👨‍💻 Author

**Ankit Gupta**

🔗 **GitHub:** [@ankitkgupta11-g](https://github.com/ankitkgupta11-g)

---

⭐ If you found this project useful, consider giving it a star on GitHub!
