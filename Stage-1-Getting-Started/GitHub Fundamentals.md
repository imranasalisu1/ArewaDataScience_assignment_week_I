# Assignment: GitHub Fundamentals

The goal of this assignment is to get familiar with using GitHub, a powerful platform for version control and collaboration in software development. By the end, you should be comfortable with creating repositories, making commits, using branches, practicing pushes, and collaborating through pull requests.

---

## Task Overview

1. **Create a GitHub Account**
   - If you don’t already have one, create an account on [GitHub](https://github.com/).

2. **Setup Git on Your Local Machine**
   - Install Git on your computer (if not already installed).
   - Configure Git with your GitHub account credentials:
     ```bash
     git config --global user.name "Your Name"
     git config --global user.email "your.email@example.com"
     ```

3. **Create a New Repository**
   - Go to your GitHub profile, create a new repository named **"GitHub_Practice"**.
   - Initialize the repository with a `README.md` file and a `.gitignore` file (choose Python if you’re primarily coding in Python).

4. **Clone the Repository to Your Local Machine**
   - Copy the repository link and clone it:
     ```bash
     git clone <your-repo-url>
     ```

5. **Edit the `README.md`**
   - Open the `README.md` file in your text editor and add:
     - A brief description of what this repository is about.
     - Your name and a short bio.

6. **Commit and Push Your Changes**
   - Save your changes and commit them:
     ```bash
     git add README.md
     git commit -m "Updated README with project description and bio"
     ```
   - **Push** your changes to GitHub:
     ```bash
     git push origin main
     ```
   - **Practice Push**: Make another small edit in the `README.md` file (e.g., add the current date) and repeat the commit and push steps to practice using `push` multiple times.

7. **Create a Branch**
   - Create a new branch named `feature-hello-world`:
     ```bash
     git checkout -b feature-hello-world
     ```
   - Create a Python file named `hello_world.py`, and add a simple script that prints “Hello, Arewa Data Science!”

8. **Push the Branch and Open a Pull Request**
   - Push the branch to GitHub:
     ```bash
     git push origin feature-hello-world
     ```
   - Go to your GitHub repository and open a pull request from `feature-hello-world` to `main`.
   - In the pull request description, briefly explain what you added in `hello_world.py`.

9. **Review and Merge the Pull Request**
   - Review your own pull request to make sure everything looks good.
   - Merge the pull request into the `main` branch.

10. **Delete the Branch**
    - After merging, delete the branch from GitHub and your local repository.

---

## Submission
- Provide the link to your GitHub repository and a screenshot of your merged pull request.

---

## Bonus Task (Optional)
Explore GitHub Issues and create a sample issue in your repository detailing a new feature or improvement.

---

This assignment will give you hands-on experience with the basics of GitHub and collaborative development.