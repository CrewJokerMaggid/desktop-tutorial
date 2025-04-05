---
layout: default
title: Instructions
nav_order: 2
---

## 🚀 Quickstart: How to Launch CrewJoker

Welcome to CrewJoker! This document will guide you through the steps to set up and run CrewJoker on your local machine.

### 1. **Clone the Repository**

First, clone the repository to your local machine:

```bash
git clone https://github.com/crewjoker/desktop-tutorial.git
cd desktop-tutorial
```

**Why?**  
We need a local copy to run and modify CrewJoker. By cloning the repo, you’re downloading all the necessary files to your machine.

---

### 2. **Install Dependencies**

CrewJoker requires certain dependencies. You can install them using `bundle`:

```bash
gem install bundler jekyll
bundle install
```

**Why?**  
These dependencies are required to render the site and work with markdown files. If you don’t have Jekyll installed, this command will install it for you.

---

### 3. **Run the Local Server**

Once you’ve set up everything, run the server:

```bash
bundle exec jekyll serve
```

Visit `http://localhost:4000` in your browser to see the site in action.

**Why?**  
Running the server locally gives you a live preview of the site before pushing it to GitHub Pages. You can make sure everything is working correctly.

---

### 4. **Modify the Site**

Now that you have the site running locally, feel free to edit any of the markdown files in the `docs/` folder. The most important files are:

- `index.md`: The homepage of CrewJoker
- `philosophy.md`: The core methodology of CrewJoker
- `structure.md`: The architecture and logic of the system
- `CONTRIBUTING.md`: How to contribute to the project

---

### 5. **Push Changes (If Desired)**

After making changes, you may want to push them to your GitHub repository. Here’s how:

```bash
git add .
git commit -m "Updated the instructions"
git push origin main
```

This ensures your changes are saved and visible on GitHub.

---

## 💡 Next Steps

Once you're comfortable with the basic setup, explore these sections:

- [Philosophy](philosophy.md) — Understand the principles behind CrewJoker
- [Structure](structure.md) — Learn about the components of the system
- [Contributing](CONTRIBUTING.md) — How to contribute to CrewJoker
