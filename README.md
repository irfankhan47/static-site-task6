# Irfan's Portfolio Website
Host a Static Website with GitHub Pages
Objective:
Deploy a simple HTML website using GitHub Pages.

Tools:
GitHub Pages

Deliverables:
Live website link

GitHub repository

Steps:
Create an index.html file:

This is the main file for your website that contains all the HTML structure and content.

Push the index.html file to a new GitHub repository:

Create a new repository on GitHub.

Initialize a local Git repository and add the remote repository.

Add the index.html file to your local repository.

```
git init
git add index.html
git commit -m "Initial commit with HTML file"
git remote add origin <your-repository-url>
git push -u origin main
Replace <your-repository-url> with the URL of your newly created GitHub repository.
```

Enable GitHub Pages:

Go to your GitHub repository → Settings → Pages.

Under Source, select the main branch and choose the root folder.

Click Save.

Access your live website:

After enabling GitHub Pages, you’ll receive a link where your website is hosted.

It will be something like: https://<your-username>.github.io/<your-repository-name>/.

Customize the Website with CSS (Optional, but recommended):

You can use the following CSS to make your website visually appealing:

```
body {
  font-family: 'Roboto', sans-serif;
  margin: 0;
  background-color: #f5f5f5;
  color: #333;
}
header {
  background-color: #1e90ff;
  color: white;
  padding: 20px 0;
  text-align: center;
}
nav {
  margin-top: 10px;
}
nav a {
  color: white;
  margin: 0 15px;
  text-decoration: none;
  font-weight: bold;
}
section {
  padding: 40px;
  text-align: center;
  margin: 20px 0;
  background-color: #ffffff;
  border-radius: 8px;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}
footer {
  background-color: #1e90ff;
  color: white;
  text-align: center;
  padding: 15px;
  position: fixed;
  bottom: 0;
  width: 100%;
}
.btn {
  display: inline-block;
  padding: 10px 20px;
  background-color: #1e90ff;
  color: white;
  text-decoration: none;
  border-radius: 5px;
  margin-top: 20px;
}
Add this CSS inside the <style> tag in the <head> section of your index.html file.

Commit and Push Updates:

Once you’ve customized the website, commit the changes and push them to GitHub:
```

```
git add index.html
git commit -m "Updated website with CSS customizations"
git push origin main
```

View Your Website:

Visit your GitHub Pages link again to see the updated website.

Screenshots of Git Commands
Here’s an example of the git commands you ran:

Initializing Git Repository:
```
git init
```
![git init](https://github.com/user-attachments/assets/573a4cda-045d-4193-b117-87ba87fb23c0)

Adding and Committing Changes:
```
git add index.html
git commit -m "Initial commit with HTML file"
```
![git add](https://github.com/user-attachments/assets/b80776ec-582c-452e-a8ef-b4c218ad238e)

![git commit](https://github.com/user-attachments/assets/481e86ec-a865-451e-96d1-8ba57a43bb5a)

Pushing to GitHub:
```
git remote add origin <your-repository-url>
git push -u origin main
```
![git push](https://github.com/user-attachments/assets/41ea4818-219f-429b-87ab-bc78f0c4c314)

GitHub Pages Setup:

![git hubb](https://github.com/user-attachments/assets/afc6ca61-cd99-447c-ba91-6b12270317d2)

Live Website Link:
Your live website can be accessed at:
https://<your-username>.github.io/<your-repository-name>/

![finalll](https://github.com/user-attachments/assets/0e7673b1-19e1-4a57-9762-4fa9fd6a16e5)
