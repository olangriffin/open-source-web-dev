# 🧑‍💻 Contributing to open-source-web-dev

Thank you for your interest in contributing!  
This project is a community-driven collection of **web application templates**.  
Contributions of all sizes are welcome — from documentation improvements to full new templates.

---

## 📋 Before You Start

- Make sure you have a GitHub account.
- Be respectful and follow the `CODE_OF_CONDUCT.md`.
- For anything more than a tiny fix, it’s best to **open or comment on an Issue** first.

---

## ✅ Step 1: Fork the Repository

A **fork** is your own copy of this repository on GitHub.

1. Click the **Fork** button in the top-right of this page.
2. Select your GitHub account as the destination.

You now have your own copy of `open-source-web-dev` under your account.

---

## 🔁 Step 2: Clone Your Fork

Open your terminal and run:

```bash
# Replace YOUR-USERNAME with your GitHub username
git clone https://github.com/YOUR-USERNAME/open-source-web-dev.git
cd open-source-web-dev
````

---

## 🌱 Step 3: Create a New Branch

Always work on a **new branch**, not directly on `main`.

```bash
git checkout -b <your-branch-name>
```

Examples:

```bash
git checkout -b add-fastapi-homepage
git checkout -b fix-typo-readme
```

---

## 📝 Step 4: Pick or Open an Issue

1. Go to the **Issues** tab.
2. Look for labels like:

   * `good first issue`
   * `help wanted`
3. Comment on the issue:

> Can you assign this to me?

Wait to be assigned before you start to avoid duplicate work.

If you want to propose something new (e.g., a new template), open a **new Issue** and describe your idea.

---

## 🔧 Step 5: Make Your Changes

Examples of things you can work on:

* Add routes or endpoints to an existing template (e.g., `templates/FastAPI`).
* Create a new template under `templates/`.
* Improve or add documentation (`README.md`, template READMEs).
* Add tests for an existing template.
* Tidy up structure, comments, or naming.

If a template includes Python dependencies:

```bash
pip install -r requirements.txt
```

(Do this inside the template directory if it has its own `requirements.txt`.)

---

## 🧪 Step 6: Test Your Changes (If Applicable)

If the template has tests, run them:

```bash
pytest
```

Some templates may not have tests yet — adding them is a great contribution!

---

## 💾 Step 7: Commit Your Changes

Stage your changes:

```bash
git add .
```

Create a clear, descriptive commit message:

```bash
git commit -m "Add homepage route to FastAPI template"
```

Good commit messages:

* Describe **what** you changed.
* Mention the **template** or part of the project you touched.

---

## ☁️ Step 8: Push Your Branch

Push your branch to your fork:

```bash
git push origin <your-branch-name>
```

---

## 🔀 Step 9: Open a Pull Request (PR)

1. Go to your fork on GitHub.

2. Click **Compare & pull request** (or go to the **Pull requests** tab and click **New pull request**).

3. Make sure the base repository is:

   * `olangriffin/open-source-web-dev`
   * base branch: `main`

4. Add a clear title and description:

   * What you changed.
   * Which template(s) are affected.
   * Reference the Issue number, e.g.:

     ```text
     Closes #3
     ```

5. Submit the Pull Request.

A maintainer will review your PR, request changes if needed, and merge it when it’s ready.

---

## 🧩 Coding & Template Guidelines

* Keep changes **focused** (one feature or fix per PR where possible).
* Follow the existing folder and naming patterns:

  * `templates/<TemplateName>/`
  * Each template should include its own `README.md`.
* Prefer small, incremental improvements over huge, hard-to-review PRs.
* If you introduce new dependencies, document them in the relevant `requirements.txt` and README.

---

## 💡 Ideas for “Good First Issues”

Not sure where to start? Here are examples of beginner-friendly tasks:

* Add a simple homepage route to the FastAPI template.
* Add or improve the README for a template.
* Add a `/health` or `/status` endpoint.
* Add basic tests for an existing route.
* Improve comments or inline documentation.

Check the Issues tab for current open tasks.

---

## 🤝 Community Expectations

By contributing, you agree to:

* Be respectful and constructive.
* Follow the `CODE_OF_CONDUCT.md`.
* Work transparently and respond to review feedback.

We want this to be a safe and friendly place to learn and collaborate.

---

## 📄 License

By submitting a contribution, you agree that your work will be licensed under the same license as the project: **MIT License** (see `LICENSE`).

---

Thank you for contributing to **open-source-web-dev**.
Your time and effort help others learn and build better web applications. 🙌
