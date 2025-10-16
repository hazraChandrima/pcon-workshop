# Dev Tips – A Collaborative Repository for Developers

## What You'll Learn
- How to **fork** a repository
- How to **clone** and **branch**
- How to **make commits** and **push changes**
- How to **create a Pull Request**
- How to **resolve merge conflicts**
---
## 🗂️ Repository Structure
```
dev-tips/
└── tips.md
└── contributors.md
└── README.md
└── .gitignore
```

---
## How to Contribute
Follow these steps carefully

### 1. Fork this repository
Click the **Fork** button at the top right of this page.  
This creates a copy of this repo under your GitHub account.
Your fork will look like:
```
https://github.com/<your-username>/dev-tips
```
---
### 2. Clone your fork using SSH
**Note:** Make sure you have SSH keys set up with GitHub. If not, follow [GitHub's SSH setup guide](https://docs.github.com/en/authentication/connecting-to-github-with-ssh).

Open a terminal and run:
```bash
git clone git@github.com:<your-username>/dev-tips.git
```
Then navigate into the folder:
```bash
cd dev-tips
```
---
### 3. Create a new branch
Always create a new branch for your changes:
```bash
git checkout -b add-my-tip
```
---
### 4. Add your tip in tips.md
Add your tip at the bottom of the file like this:
```markdown
- Always write meaningful commit messages. *(Added by Chandrima Hazra)*
```
Then, add your name to the `contributors.md` file:
```markdown
- Chandrima Hazra
```
---
### 5. Commit your changes
```bash
git add .
git commit -m "<commit message here>"
```
---
### 6. Push your branch
```bash
git push origin add-my-tip
```
---
### 7. Create a Pull Request
1. Go to your fork on GitHub.
2. You'll see a prompt to "Compare & pull request".
3. Click it, add a short description, and submit your PR.
   Wait for the maintainer to review and merge your contribution
---