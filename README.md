# OpenIQX Members

Welcome to the **OpenIQX Members Repository**.

This repository serves as the **official registry of all OpenIQX community members**.

Every member has their **own markdown file** in this repository where they introduce themselves and track their **open source contributions**.

But more importantly, this repository exists to ensure that **every new member practices the real open-source workflow before officially joining the community**.

If you can successfully submit your profile here, it means you have already practiced the core skills required to contribute to open source.

---

# Why This Repository Exists

Many people join open source communities but never actually make a contribution because the process feels confusing.

This repository solves that problem.

Before you are considered a **full OpenIQX member**, you must:

* Fork a repository
* Clone it locally
* Create a feature branch
* Make a change
* Commit your change
* Push your branch
* Open a Pull Request

By completing these steps, you will already have completed your **first real open-source workflow**.

---

# You Are Not Officially a Member Until

Your personal profile file has been:

* Created
* Submitted via Pull Request
* Reviewed
* Merged into `main`

Once your PR is merged, you are officially an **OpenIQX member**.

---

# Repository Structure

```
openiqx-members/
│
├── README.md
├── template.md
└── members/
    ├── README.md
    ├── example.md
    └── your-name.md
```

Each member creates their own file inside the **members/** directory.

The file name should be your **full name in lowercase** with hyphens.

Example:

```
sam-looke.md
mary-smith.md
alex-johnson.md
```

---

# How to Join OpenIQX (Step-by-Step)

Follow these steps carefully.

### 1. Fork This Repository

Click the **Fork** button on GitHub to create your own copy of this repository.

---

### 2. Clone Your Fork

```
git clone https://github.com/openiqx/openiqx-members.git
```

Move into the repository:

```
cd openiqx-members
```

---

### 3. Create a Feature Branch

```
git checkout -b feat/add-your-name
```

---

### 4. Create Your Profile File

Navigate to the `members/` directory.

Create a new markdown file with your name.

Example:

```
members/john-doe.md
```

You can use **template.md** as your starting point.

---

### 5. Add Your Information

Fill in your details including:

* Name
* Programming languages
* GitHub
* LinkedIn
* Open source contributions

Only include **merged pull requests** in the Open source contributions section, if available or leave empty.

---

### 6. Commit Your Change

```
git add .
git commit -m "Add profile for <your-fullname>"
```

---

### 7. Push Your Branch

```
git push origin feat/add-your-name
```

---

### 8. Open a Pull Request

Go to GitHub and open a Pull Request from your branch to `main`.


---

### 9. Wait for the **automated validation workflow** to pass.

Wait for the validation workflow to pass and your PR to be merged.

---

### 10. . Once approved and merged 

You are officially an **OpenIQX member**.


> **Tip:** Only update your file when you have new **merged PRs** to add to your Open Source Contributions section.

---

# Tracking Your Open Source Contributions

Your file will act as your **personal open source record** inside the OpenIQX community.

Each time you make a **merged contribution**, update your file and submit another PR.

This helps you:

* Track your progress
* Showcase your contributions
* Build a visible portfolio for recruiters

---

# Example Contribution Entry

```
# Open Source Contributions

## awesome-project
- PR: https://github.com/username/awesome-project/pull/56
- PR: https://github.com/username/awesome-project/pull/60

## another-project
- PR: https://github.com/otheruser/another-project/pull/18
```

Only include **merged pull requests**.

---

# Tips for Maintaining Your Profile

Update your file when:

* A new PR is merged
* You want to update your links

Over time, your file will become a **timeline of your open source journey**.

---

## Recommended Template

We provide `example.md` as a reference. Please follow its structure carefully.

---

## Automation & Validation

* This repository uses **GitHub Actions** to:

  * Validate that each member file is correctly formatted.
  * Automatically update the `members/README.md` with new members.

* Pull Requests that **do not follow the correct structure will fail validation**.

---

## Why We Do This

* Ensures every member **practices proper Git workflow**.
* Maintains **a clean, consistent record** of community members.
* Creates a **single source of truth** for recruiters, collaborators, and other community members.

---

Welcome to OpenIQX - **your journey as an open-source contributor starts here!**
