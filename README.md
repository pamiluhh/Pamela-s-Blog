<div align="center">
<img width="1200" height="475" alt="GHBanner" src="https://github.com/user-attachments/assets/0aa67016-6eaf-458a-adb2-6e31a0763ed6" />
</div>

# Pamela's Blog

A modern, full-featured blog platform built with React, Firebase, and Tailwind CSS. This project features a seamless visitor experience and a robust administrative dashboard for content management.

## 🌟 Key Features

### 📖 Visitor Experience
- **Dynamic Content**: View and read blog posts with real-time updates.
- **Interactive Comments**: Engage with content through a real-time commenting system.
- **Post Reactions**: React to posts to show appreciation.
- **Search & Navigation**: Seamlessly search for topics and navigate through categories.
- **Login/Account System**: Required for personalized interactions.
- **Responsive Design**: Fully optimized for mobile, tablet, and desktop views.

### 🔐 Administrative Dashboard
- **Content Management**: Create, edit, and delete blog posts with a rich text editor.
- **Real-time Analytics**: Track visitor activities and post views.
- **Comment Moderation**: Manage and respond to visitor comments.
- **Feedback Management**: View and handle user feedback efficiently.
- **Secure Authentication**: Protected admin access for site management.

## 🛠️ Tech Stack

- **Frontend**: React (with Vite), TypeScript
- **Styling**: Tailwind CSS, Lucide React (Icons), Motion (Animations)
- **Backend & Database**: Firebase Realtime Database
- **AI Integration**: Google Gemini AI (for content assistance)
- **Routing**: React Router DOM

## 📂 Project Structure

```text
src/
├── components/     # Reusable UI components (Navbar, Footer, etc.)
├── pages/          # Page components (Home, PostDetails, AdminDashboard, etc.)
├── firebase.ts     # Firebase configuration and initialization
├── types.ts        # TypeScript interfaces and types
└── utils/          # Helper functions
```

## 🚀 Run Locally

**Prerequisites:** Node.js (v18+)

1. **Clone the Repository:**
   ```bash
   git clone [repository-url]
   cd pamela-s-blog
   ```

2. **Install Dependencies:**
   ```bash
   npm install
   ```

3. **Environment Setup:**
   Create a `.env` file in the root directory (using `.env.example` as a template) and add your credentials:
   - `GEMINI_API_KEY`: Your Google Gemini API Key
   - Firebase configuration details

4. **Start the Development Server:**
   ```bash
   npm run dev
   ```
   The app will be available at `http://localhost:3000`.

## 🌐 Deployment

View the live app in AI Studio: [Pamela's Blog - AI Studio](https://ai.studio/apps/c070379d-885c-49c3-9221-b766b774bff4)

