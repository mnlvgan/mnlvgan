# Vincent Gilbert A. Nunez - IT Student

Hello! 👋 I'm Vincent Gilbert A. Nunez, a second-year IT student at Mapua Malayan Colleges Laguna. I'm passionate about exploring the diverse realms of information technology.

## About Me

- 🎓 Currently in my second year at Mapua Malayan Colleges Laguna.
- 🌐 Committed to staying updated on the latest tech trends and innovations.

## Connect with Me

Feel free to connect with me! Let's collaborate, share knowledge, and explore the exciting world of technology together.

- 📧 Email: [vincentgilbert@gmail.com](mailto:vincentgilbert@gmail.com)
- 💻 GitHub: [mnlvgan](https://github.com/mnlvgan)

Looking forward to connecting with fellow tech enthusiasts! 🚀


## Git Commands Cheat Sheet

Welcome to the Git Commands Cheat Sheet!🌌

### 1. **`git clone`**
   - **Usage:** Copy a repository from the web to your computer.
   - **When to use:** When you want to grab a full project from GitHub to tinker with.
   - **Parameters:** Repository URL.
   - **Example:**
     ```bash
     git clone https://github.com/mnlvgan/mnlvgan.git
     ```

### 2. **`git branch`**
   - **Usage:** Check, create, or delete branches in your project.
   - **When to use:** When you want to organize your work, and each branch can be a different task or feature.
   - **Parameters:**
     - `-a`: List all branches.
     - `-d`: Delete a branch.
     - `<branch-name>`: Create a new branch.
   - **Examples:**
     ```bash
     git branch          # List all branches
     git branch new-feature    # Create a new branch
     git branch -d feature-branch    # Delete a branch
     ```

### 3. **`git pull`**
   - **Usage:** Get the latest changes from others working on the project.
   - **When to use:** To keep your local copy up to date with what's happening in the shared project.
   - **Parameters:** None.
   - **Example:**
     ```bash
     git pull origin main
     ```

### 4. **`git commit`**
   - **Usage:** Save your changes with a little note about what you did.
   - **When to use:** To record changes and provide context about the changes made.
   - **Parameters:**
     - `-m`: Add a commit message.
   - **Example:**
     ```bash
     git commit -m "Fixed a bug in login page"
     ```

### 5. **`git stash`**
   - **Usage:** Save your work temporarily, so you can switch to something else.
   - **When to use:** When you're in the middle of something but need to work on a different task.
   - **Parameters:**
     - `save`: Save the stash with a message.
   - **Example:**
     ```bash
     git stash save "Trying out a new idea"
     ```

### 6. **`git diff`**
   - **Usage:** Displays the differences not added to the index. Also views the changes you have in your workspace relative to the named commit.
   - **When to use:** When you want to look at current changes in your working copy, past changes in commits, or even to compare branches.
   - **Parameters:**
     - `commit or branch`: Specifies what to compare
   - **Example:**
     ```bash
     diff --git a/diff_test.txt b/diff_test.txt
     ```

### 7. **`git revert`**
   - **Usage:** Reverse commit specified by commit and commit the result.
   - **When to use:** When you want to apply the inverse of a commit from your project history.
   - **Parameters:**
     - `commit`: Specifies the commit to be reversed
   - **Example:**
     ```bash
     git revert HEAD
     ```

