

## 🧾 Table of Contents
- [How to Contribute](#-how-to-contribute)
- [Contribution Guidelines](#-contribution-guidelines)
- [Pull Request Process](#-pull-request-process)
- [Reporting Issues](#-reporting-issues)
- [License](#-license)
- [Copyright Notice](#-copyright-notice)

---

## 🏢 How to Contribute

1. **Fork the repository** 📚
2. **Clone your fork (Only the dev Branch)**
   ```bash
   git clone --branch dev 
   ```
3. **Navigate into the project directory**
   ```bash
   cd Restaurant-Menu-Management-System
   ```
4. **Create a new branch** 🌿
   ```bash
   git checkout -b feature/your-feature-name
   ```

5. **Navigate to the backend and frontend directories**
   ```bash
   cd ./backend/
   npm install

   cd ./frontend/
   npm install
   ```

6. **Set up environment variables**
   - Create a `.env` file in both `backend` and `frontend` using `.env.example` as a reference.

7. **Run the backend server** (Port: `8000`)
   ```bash
   cd backend
   npm run dev
   ```

8. **Run the frontend server** (Port: `5173`)
   ```bash
   cd frontend
   npm run dev
   ```
9. **Make your changes** ✨
10. **Commit your changes** 💾
   ```bash
   git commit -m "Add: A meaningful commit message"
   ```
11. **Push to your branch** 👤
   ```bash
   git push origin feature/your-feature-name
   ```
12. **Create a Pull Request** 🛠️

---

## 📋 Contribution Guidelines

- Follow the existing code style and naming conventions.
- Write clear, concise commit messages.
- Add comments where necessary.

---

## ✅ Pull Request Process

- Always branch out from the `dev` branch.
- Submit your pull request to the `dev` branch.
- Ensure your PR is linked to an issue if applicable.
- Wait for approval before merging.
- Only maintainers can merge into the `master` branch.

---

## 📝 License

This project is licensed under the [MIT License](LICENSE).

Happy Coding! 💻🎉

