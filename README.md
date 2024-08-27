# ✨ Node Project Starter Template ✨

🚀 Kickstart your Node.js development with this streamlined template! 🚀

This template is pre-configured with essential tools and settings to ensure code quality and consistency:

- **ESLint:** Catches potential code errors and style issues.
- **Prettier:** Automatically formats your code for a clean, consistent look.
- **Jest:** Simplifies unit testing with a powerful framework.
- **Husky:** Automates tasks with Git hooks.
- **Lint-staged:** Runs linters and formatters only on staged files.
- **Pre-commit Hook:** Ensures code quality by running ESLint, Prettier, and Jest before each commit.

## 🚀 Getting Started

Follow these steps to set up the project with your own repository:

0. **Clone the Repository:**

   - Clone this repository to your local machine using the following command:

     ```bash
     git clone https://github.com/leonbubova/node-starter.git
     ```

1. **Rename the Folder:**

   - Change the project folder's name to your desired project name.

2. **Rename `package.json`:**

   - Open `package.json` and update the `name` property to match your project name.

3. **Remove Existing Git:**

   - Delete the existing Git history:

     ```bash
     rm -rf .git
     ```

4. **Create a New Repository:**

   - On your Git hosting platform (e.g., GitHub, GitLab), create a new empty repository with the same name as your project.

5. **Initialize Git:**

   ```bash
   git init
   git branch -m main
   ```

6. **Add Remote:**

   ```bash
   git remote add origin https://[YOUR USERNAME]@github.com:[YOUR USERNAME]/[YOUR REPO NAME].git
   ```

7. **Install dependencies**

   ```bash
   npm i
   ```

8. **Initial Commit and Push:**

   ```bash
   git add .
   git commit -m "initial commit"
   git config --global credential.helper store // optional
   git push -u origin main
   ```

## 💡 Important Notes

- **Replace Placeholders:** In the `git remote add origin` command, replace `[YOUR USERNAME]` and `[YOUR REPO NAME]` with your actual username and repository name.
- **Store Credentials:** The `git config --global credential.helper store` command will securely store your Git credentials for future use.

## 🎉 Success!

You're all set! Your project is now connected to its own Git repository and ready for development. Leverage the pre-configured tools to write clean, consistent, and well-tested code!

Happy coding! 😄
