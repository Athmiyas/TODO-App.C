# ✅ TODO List App

A simple and secure TODO List application built with **React Native (Expo)**, **Clerk Authentication**, and **Supabase** as the backend.  
Users can register or sign in, add their daily tasks, mark them as completed, and delete them easily.

---

## 🚀 Features

- 🔐 **User Authentication** using Clerk (Google or Email login)
- 🗂️ **Supabase Database** for secure task storage
- ✍️ Add, edit, and delete tasks
- ✅ Mark tasks as completed
- 📱 Clean and responsive UI built with React Native (Expo)
- ☁️ Data stored per user (tasks are private to each user)

---

## 🛠️ Tech Stack

| Technology | Purpose |
|-------------|----------|
| **React Native (Expo)** | Frontend framework |
| **Clerk** | Authentication (Google/Email) |
| **Supabase** | Database & Backend |
| **JavaScript / TypeScript** | Programming language |

---

## ⚙️ Installation & Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/todo-app.git
   cd todo-app
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   Create a `.env` file in the root folder and add:
   ```bash
   EXPO_PUBLIC_SUPABASE_URL=your_supabase_url
   EXPO_PUBLIC_SUPABASE_ANON_KEY=your_supabase_anon_key
   EXPO_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_key
   ```

4. **Run the app**
   ```bash
   npx expo start
   ```

---

## 📂 Project Structure

```
/todo-app
│
├── app/
│   ├── (auth)/          # Login and signup screens
│   ├── (todos)/         # Main TODO screen (protected)
│   ├── _layout.js       # Navigation layout
│   └── index.js         # Entry point
│
├── lib/
│   ├── supabase.js      # Supabase client setup
│   ├── clerk.js         # Clerk configuration
│
├── components/
│   ├── TodoItem.js      # Component for displaying tasks
│   └── AddTodo.js       # Input for adding new tasks
│
├── .env                 # Environment variables
├── package.json
└── README.md
```

---

## 🧑‍💻 Usage

- Sign in using Clerk authentication.
- Create new TODO items.
- Tap to mark tasks as **completed** or **incomplete**.
- Swipe or long press to **delete** tasks.

---

## 📸 Screenshots
*(Add screenshots of your app here if available)*

---

## 📜 License

This project is open source and available under the [MIT License](LICENSE).

---

## 🙌 Acknowledgements

- [Clerk.dev](https://clerk.com/)
- [Supabase](https://supabase.com/)
- [Expo](https://expo.dev/)
- [React Native](https://reactnative.dev/)
