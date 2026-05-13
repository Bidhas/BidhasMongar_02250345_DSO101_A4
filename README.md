A simple static website deployed using GitHub Actions and Render. 
Live URL

[https://bidhasmongar-02250345-dso101-a4.onrender.com]

Tools Used

- **GitHub** – version control and repository hosting
- **GitHub Actions** – CI/CD pipeline (auto-runs on every push to `main`)
- **Render** – static site deployment


Steps to Deploy

1. Clone or create the repo

git init
git add .
git commit -m "first commit"
git branch -M main
git remote add origin <your-repo-url>
git push -u origin main


2. GitHub Actions
- The workflow file at `.github/workflows/deploy.yml` runs automatically on every push to `main`.
- It checks out the code and confirms the push was successful.

3. Render Deployment
1. Go to [https://render.com](https://render.com)
2. Sign in with GitHub
3. Click **New → Static Site**
4. Connect this repository
5. Set **Publish Directory** to `.`
6. Click **Deploy**


Verification

![alt text](image.png)
![alt text](image-1.png)