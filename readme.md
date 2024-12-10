![Alt text](./assets/onja_logo.png)

# Github

you’ve created a file on your device, and now you want to store it online for easy access and sharing. For this, we use GitHub. Tomorrow, we’ll dive deep into understanding Git, but today, let’s focus on getting your portfolio markdown page onto GitHub.

## Steps to Upload Your Markdown File to GitHub

1. **Sign Up or Log In to GitHub**  
   if you don’t already have an account, go to [GitHub](https://github.com/) and sign up.

2. **Create a New Repository**  
   Click the green **`New`** button on GitHub’s main page to create a new folder (known as a “repository”) for your project.

3. **Open the Command Line**  
   open your Command Line (CMD) and navigate to the folder where you stored your markdown file.

4. **Initialize Git and Add Files**  
   type the following commands in sequence to prepare your folder for GitHub. We’ll learn the details tomorrow, but for now, follow these steps:
   ```bash
   git init
   git add .
   git commit -m "Initial commit with portfolio markdown file"
    ```

5. **Link to Your Online Repository**
    After running the commands above, type the following to connect your local folder to the GitHub repository:
    ```bash
    git remote add origin <URL of your GitHub repository>
    git branch -M main
    git push -u origin main
    ```


6. **Check Your GitHub Repository**
    Once you’ve successfully run these commands, refresh your repository page on GitHub. You should now see your markdown file displayed there.