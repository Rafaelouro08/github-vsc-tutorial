# 🚀 Quick Git & GitHub with VS Code Tutorial

This repo is a simple HTML/CSS/JS project to help you practice using **Git** and **GitHub** inside **VS Code**.  
Follow the steps below to learn the essential workflow: clone → edit → commit → branch → push → pull request → merge.  

---

## 1. Setup
- Install **[Git](https://git-scm.com/downloads)**.  
- Install **[VS Code](https://code.visualstudio.com/)**.  
- In VS Code, install the extension:  
  - **GitHub Pull Requests and Issues**

---

## 2. Clone the Repo
1. Copy the URL of this repository.  
2. In VS Code:
   - Open the **Command Palette** (`Ctrl+Shift+P` / `Cmd+Shift+P`).  
   - Run: `Git: Clone` → paste the repo URL.  
   - Open the cloned folder in VS Code.  

---

## 3. Explore & Edit
- Open `index.html` or `style.css`.  
- Make a small change, like updating the heading in `index.html`:

```html
<h1>Hello World</h1>
````

➡ Change to:

```html
<h1>Hello Git!</h1>
```

Or tweak a CSS color in `style.css`.

---

## 4. Stage & Commit

1. Go to the **Source Control** tab in VS Code (left sidebar, Git icon).
2. You’ll see your changed files.
3. Hover over them and click **+** to **Stage Changes**.
4. Enter a commit message (e.g., `Updated heading text`).
5. Click **✔ Commit**.

---

## 5. Create & Switch Branches

* Open the **Command Palette** → run: `Git: Create Branch`.
* Name it something like `feature-update`.
* Make another small change (e.g., change a button color in CSS).
* Commit again with a message like: `Changed button background color`.

---

## 6. Push to GitHub

* Click the **Sync Changes** button (↑↓) in the Source Control tab.
* This uploads your commits and branch to GitHub.

---

## 7. Open a Pull Request (PR)

1. Go to the repository on GitHub in your browser.
2. You’ll see a banner to create a Pull Request from your new branch.
3. Click **Compare & pull request**.
4. Add a description and click **Create pull request**.

---

## 8. Merge the PR

* On GitHub, review your changes in the PR.
* Click **Merge pull request** → **Confirm merge**.
* Back in VS Code, click **Sync Changes** so your local `main` matches GitHub.

---

## 9. Bonus Tips (Optional)

* Run `git log` in the VS Code terminal to see commit history.
* Right-click a changed file → **Discard Changes** to undo edits.
* Add files to `.gitignore` to stop them being tracked.

---

✅ You’ve now practiced the full GitHub workflow:
**Clone → Edit → Commit → Branch → Push → Pull Request → Merge → Sync**

---

Happy coding! 🎉

```

Do you want me to also generate a **starter repo scaffold** (basic `index.html`, `style.css`, `script.js`) that matches the tutorial, so learners can immediately follow along?
```
