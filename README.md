# 🌱 SkillTree

**SkillTree** is an interactive web application that enables users to create, manage, and share personalized skill trees for learning, career development, or personal growth. Visualize your progress, set dependencies between skills, and track your journey in a structured and engaging way.

## 🚀 Features

- **User Authentication**: Secure registration and login with JWT-based authentication.
- **Custom Skill Trees**: Create and edit skill trees using a drag-and-drop interface.
- **Skill Dependencies**: Define prerequisites between skills to map out learning paths.
- **Progress Tracking**: Mark skills as planned, in progress, or completed.
- **Public/Private Trees**: Choose to keep your skill trees private or share them publicly.
- **Data Export/Import**: Export your skill trees to JSON and import them back anytime.
- **Responsive Design**: Fully responsive layout for desktop and mobile devices.

## 🛠️ Tech Stack

### Frontend

- [React](https://reactjs.org/) with [TypeScript](https://www.typescriptlang.org/)
- [Tailwind CSS](https://tailwindcss.com/) for styling
- [React Flow](https://reactflow.dev/) for interactive diagrams
- [Zustand](https://zustand-demo.pmnd.rs/) for state management

### Backend

- [Node.js](https://nodejs.org/) with [Express](https://expressjs.com/) or [NestJS](https://nestjs.com/)
- [MongoDB](https://www.mongodb.com/) with [Mongoose](https://mongoosejs.com/)
- [JWT](https://jwt.io/) for authentication
- [bcrypt](https://github.com/kelektiv/node.bcrypt.js/) for password hashing

### Deployment

- Frontend: [Vercel](https://vercel.com/) or [Netlify](https://www.netlify.com/)
- Backend: [Render](https://render.com/) or [Railway](https://railway.app/)
- Database: [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)
- CI/CD: [GitHub Actions](https://github.com/features/actions)

## 📸 Screenshots

![Dashboard](./screenshots/dashboard.png)
*Dashboard view with multiple skill trees.*

![Skill Tree Editor](./screenshots/editor.png)
*Drag-and-drop interface for creating and editing skill trees.*

## 📦 Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/yourusername/skilltree.git
   cd skilltree
