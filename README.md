# 🤖 Creator AI – AI-Powered Content Generator

**Creator AI** is an AI-powered content generation platform built to help users create high-quality content quickly and efficiently using Google's **Gemini AI**.

The application provides a modern and responsive interface with secure authentication, AI-powered content generation, content history, usage tracking, subscription management, and database integration.

---

## 🚀 Features

* 🤖 **AI-Powered Content Generation**

  * Generate high-quality content using the Google Gemini API.
  * Multiple content-generation templates for different use cases.

* 🔐 **Secure Authentication**

  * User authentication and account management powered by Clerk.
  * Protected dashboard and user-specific features.

* 📝 **Content Templates**

  * Predefined templates to make content creation faster and easier.
  * Search and select templates based on your requirements.

* 📚 **Content History**

  * View previously generated content.
  * Easily copy generated content for further use.

* 📊 **Usage Tracking**

  * Track AI credit usage.
  * Monitor content-generation limits.

* 💳 **Subscription & Billing**

  * Subscription management and credit-based usage system.
  * Integrated payment functionality.

* 🎨 **Modern & Responsive UI**

  * Clean dashboard interface.
  * Responsive design using Tailwind CSS.

* 🗄️ **Database Integration**

  * PostgreSQL database for storing application and user data.
  * Drizzle ORM for database management.

---

## 🛠️ Tech Stack

| Technology            | Usage                            |
| --------------------- | -------------------------------- |
| **Next.js**           | Full-stack React framework       |
| **React.js**          | Frontend UI                      |
| **TypeScript**        | Type-safe development            |
| **Tailwind CSS**      | Styling and responsive UI        |
| **Clerk**             | Authentication & user management |
| **Google Gemini API** | AI content generation            |
| **PostgreSQL**        | Database                         |
| **Drizzle ORM**       | Database ORM                     |
| **Vercel**            | Deployment                       |

---

## 📂 Project Structure

```text
Creator-AI/
│
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

---

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

Create a `.env.local` file in the root directory:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
DATABASE_URL=your_postgresql_database_url
GEMINI_API_KEY=your_gemini_api_key
```

> ⚠️ **Never commit your `.env.local` file or expose your API keys publicly.**

### 5. Start the Development Server

```bash
npm run dev
```

Open your browser and visit:

```text
http://localhost:3000
```

---

## 🔄 How It Works

```text
User
  ↓
Select Content Template
  ↓
Enter Required Information
  ↓
Send Prompt
  ↓
Google Gemini API
  ↓
AI Generated Content
  ↓
Display & Save Content
```

---

## 🌐 Live Demo

Add your deployed Vercel URL here:

**Live Demo:** [Creator AI](YOUR_VERCEL_URL)

---

## 📸 Screenshots

Screenshots of the application can be added here to showcase the dashboard, content generation interface, authentication pages, and generated content.

---

## 🔮 Future Enhancements

* Support for additional AI models
* More content-generation templates
* Advanced content analytics
* AI-powered content suggestions
* Team collaboration features
* Improved content customization
* Export generated content to different formats
* Enhanced subscription plans

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a new branch.

```bash
git checkout -b feature/your-feature
```

3. Make your changes.
4. Commit your changes.

```bash
git commit -m "Add new feature"
```

5. Push the branch.

```bash
git push origin feature/your-feature
```

6. Open a Pull Request.

---

## 📄 License

This project is licensed under the **MIT License**.

---

## 👨‍💻 Author

**Ankit Gupta**

GitHub: [@ankitkgupta11-g](https://github.com/ankitkgupta11-g)

---

⭐ If you found this project useful, consider giving it a **star** on GitHub!
