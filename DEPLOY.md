# Deploy For Yogart to Netlify

Follow these steps to initialize your project and deploy it.

1.  **Initialize Git**
    Run the following command to start tracking your files.
    ```bash
    git init
    ```

2.  **Add Files**
    Stage all your files for the first commit.
    ```bash
    git add .
    ```

3.  **Commit Changes**
    Save your changes.
    ```bash
    git commit -m "Initial commit: Restructure project for Netlify"
    ```

4.  **Create a Repository on GitHub**
    - Go to [GitHub.com](https://github.com/new).
    - Create a new repository named `foryogart`.
    - Do **not** initialize with README, license, or .gitignore (we already have them).

5.  **Connect to Remote**
    Replace `YOUR_USERNAME` with your actual GitHub username and run this command.
    ```bash
    git remote add origin https://github.com/YOUR_USERNAME/foryogart.git
    git branch -M main
    git push -u origin main
    ```

6.  **Deploy on Netlify**
    - Go to [Netlify](https://app.netlify.com).
    - Click "Add new site" > "Import from Git".
    - Choose GitHub and select your `foryogart` repository.
    - Click "Deploy".
    - Your site will be live!
