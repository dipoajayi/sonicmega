# Sonic Mega Website

This is the repository for the Sonic Mega website.

## Deployment to GitHub Pages

To deploy this website to GitHub Pages, follow these steps:

1.  **Create a new repository on GitHub.**
    You can do this by going to [https://github.com/new](https://github.com/new).

2.  **Initialize a git repository in your project folder.**
    Open your terminal, navigate to the project folder, and run the following command:
    ```bash
    git init
    ```

3.  **Add all the files to the staging area.**
    ```bash
    git add .
    ```

4.  **Commit the files.**
    ```bash
    git commit -m "Initial commit"
    ```

5.  **Add the remote repository.**
    Replace `<your-username>` and `<your-repository-name>` with your GitHub username and the name of the repository you created in step 1.
    ```bash
    git remote add origin https://github.com/<your-username>/<your-repository-name>.git
    ```

6.  **Push the files to the remote repository.**
    ```bash
    git push -u origin main
    ```

7.  **Enable GitHub Pages in the repository settings.**
    - Go to your repository on GitHub.
    - Click on the "Settings" tab.
    - In the left sidebar, click on "Pages".
    - Under "Source", select the `main` branch and the `/ (root)` folder, then click "Save".

8.  **Your website will be available at `https://<your-username>.github.io/<your-repository-name>/`.**
    It may take a few minutes for the website to be deployed.