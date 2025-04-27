# X-Plane-Menu-Hugo

[![Build Status](https://img.shields.io/github/actions/workflow/status/1090MHz/X-Plane-Menu-Hugo/hugo.yaml?branch=main)](https://github.com/1090MHz/X-Plane-Menu-Hugo/actions)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

---

This repository contains a **Hugo** project styled using the **AltitudeDark** theme, which is designed to replicate the look and feel of the X-Plane menu. With clean separators and nested submenus, the layout reflects the intuitive and structured design of the X-Plane interface.

⚠️ **Note:** The menu is non-functional — this is a visual demo only.

---

## 📦 Clone the Repository with Submodules

To clone this repository along with its submodules, use the following command:

```bash
git clone --recurse-submodules https://github.com/1090MHz/X-Plane-Menu-Hugo.git
```

---

## 🛠 If You Forgot to Clone Submodules

If you cloned the repository without the `--recurse-submodules` flag, you can initialize and update the submodules afterward with these commands:

```bash
git submodule update --init --recursive
```

To ensure the submodules are fully synced with the remote repository, you can also run:

```bash
git submodule sync
```

---

## 🧱 Building the AltitudeDark Theme

The **AltitudeDark** theme uses Tailwind CSS, and the `tailwind.css` file needs to be built before running the site. Follow these steps:

1. Navigate to the theme directory:
   ```bash
   cd themes/AltitudeDark
   ```

2. Install the required dependencies:
   ```bash
   npm install
   ```

3. Build the CSS file:
   - For a one-time build:
     ```bash
     npm run build
     ```
   - For development with live updates:
     ```bash
     npm run dev
     ```

After building the CSS file using `npm run build` (or `npm run dev` for live updates), you can run the Hugo site as usual by executing `hugo server` in the root directory of the project.

---

## 🔄 Updating Submodules

To update submodules with the latest remote changes, run:

```bash
git submodule update --remote --merge
```

---

## 📝 Additional Notes

- The site uses the **AltitudeDark** theme by default.
- This theme does not include a prebuilt `tailwind.css` file to allow full flexibility for customization and development.
- Additionally themes are included for experimentation and are not strictly required.

---
