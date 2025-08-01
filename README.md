# 🎨 GraphicDesign TechStack2025 

Welcome to the official repository for the **Graphic Design Branch**.  
This repo is where students will submit their homework assignments (e.g., PSD and JPG files) via **pull requests**.

All students are required to:
- Use **Git** and **GitHub**
- Submit their work **via a personal branch**
- Follow the structure and naming conventions outlined below

---

## 📁 Folder Structure

Each assignment has its own folder.  
Inside each assignment folder, students create a subfolder **with their full name or GitHub username** and place their work there.

```
/Assignment1/
  └── YourName/
       ├── final-design.psd
       ├── preview.jpg
       └── README.md (optional: brief explanation)

Example:
Assignment1/
  └── Sara-Ahmadi/
       ├── poster-v1.psd
       ├── poster-v1.jpg
       └── README.md
```

---

## ✅ What You Must Submit

Each homework must include:
- `.psd, .prproj, .fig, etc.` (working source file)
- `.jpg, .png, .mp4, .mp3, etc.` (preview/exported)

Optional:
- `README.md` inside your folder (explaining your design idea/tools/process)

---

## 🪜 Step-by-Step Submission Instructions

1. **Fork** this repository to your own GitHub account.
2. **Clone** the fork to your local computer:
   ```bash
   git clone https://github.com/anjrzdgn/GraphicDesign_TechStack_2025
   cd graphic-homeworks
   ```
3. **Create a new branch with your name**:
   ```bash
   git checkout -b your-name
   ```
   > Example: `git checkout -b sara-ahmadi`

4. Go to the related assignment folder (e.g., `Assignment1`) and **create a subfolder with your name**. Place your files inside.

5. **Stage, commit, and push your changes**:
   ```bash
   git add .
   git commit -m "Add homework for Assignment1 - Sara Ahmadi"
   git push origin your-name
   ```

6. Go to your fork on GitHub and click **"New Pull Request"**.

7. Submit the pull request from your branch (e.g., `sara-ahmadi`) to the **main repo's `main` branch**.

---

## ✍️ Pull Request Guidelines

Every pull request must:
- Be from **your personal branch**
- Have a **clear title**, e.g. `Add Assignment 1 - Sara Ahmadi`
- Include a description (optional but recommended)
- Be submitted **before the deadline**

---

## 💡 Naming Standards

| Type         | Naming Standard       | Example             |
|--------------|------------------------|---------------------|
| Folder name  | `FirstName-LastName`   | `Sara-Ahmadi`       |
| PSD file     | `name-vX.psd`          | `poster-v1.psd`     |
| JPG preview  | `name-vX.jpg`          | `poster-v1.jpg`     |

---

## 📦 Git LFS — For Large Files

Since `.psd` files can be large, **you must install Git LFS** before committing them.

### Install Git LFS:
```bash
# Only once on your system
git lfs install
```

### Track PSD files:
```bash
git lfs track "*.psd"
```

Make sure `.gitattributes` file includes:
```
*.psd filter=lfs diff=lfs merge=lfs -text
```

---

## 🛑 Important Rules
> [!IMPORTANT]
> ❗️**Always work on your own branch** (named after you) 
>> 📁 **Put your work in the correct assignment folder**

> [!CAUTION]
> 🧠 **Do not edit or touch other students' folders**

---

## ❓ Common Issues

| Issue | Solution |
|-------|----------|
| Forgot to use LFS for PSD | Remove PSD, track with LFS, and recommit |
| Committed to `main` instead of personal branch | Create new branch, cherry-pick commits |
| Forgot to add `.jpg` | Commit again in the same branch and push |

---

## 📞 Need Help?

If you face issues with Git, GitHub, or file formats, please reach out during class or contact with [ME](https://alinajarzadegan1383@gmail.com).

---

**Happy designing! 🎨🔥**
