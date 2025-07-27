# My Gitignore Boilerplate

[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://github.com/KnowOneActual/gitignore-boilerplate/)
[![Last Commit](https://img.shields.io/github/last-commit/KnowOneActual/gitignore-boilerplate.svg)](https://github.com/KnowOneActual/gitignore-boilerplate/commits/main)
[![License](https.img.shields.io/github/license/KnowOneActual/gitignore-boilerplate.svg)](https://github.com/KnowOneActual/gitignore-boilerplate/blob/main/LICENSE)


This repository holds a general-purpose `.gitignore` file that I use as a starter for new projects. The goal is to have a robust, catch-all template that handles common files from different operating systems, editors, and build tools.

## Why This Exists

Instead of starting from scratch with every new project, this boilerplate provides a solid foundation that ignores:
* Operating System generated files (like `.DS_Store` or `Thumbs.db`)
* Common log and temporary files
* Editor and IDE configuration folders (like `.vscode/` or `.idea/`)
* Dependency folders (like `node_modules/`)
* Common build and distribution outputs (like `/build/` or `/dist/`)

## How to Use

There are a few easy ways to grab this file for a new project.

### Option 1: Using `curl` (Recommended)

This is the quickest way. Navigate to your project's root directory in the terminal and run the following command.

```bash
curl -L -o .gitignore https://raw.githubusercontent.com/KnowOneActual/gitignore-boilerplate/main/.gitignore
```

### Option 2: Clone and Copy

You can clone this repository to your local machine and copy the file from there.

* **First, clone the repository. This creates a new folder named "gitignore-boilerplate".**

```bash
git clone https://github.com/KnowOneActual/gitignore-boilerplate.git
```

* **Then, copy the file from the new folder to your project's location.**

```bash
cp gitignore-boilerplate/.gitignore /path/to/your/new-project/
```

### Option 3: Manual Download

You can also just view the `.gitignore` file on GitHub, click the "Raw" button, and save the page's contents into a `.gitignore` file in your project.

## Customization

This file is a great starting point, but feel free to edit it to fit the specific needs of your project. You can add project-specific ignores at the bottom or remove sections you don't need.


## **This project is licensed under the Unlicense License.**

For more information, please refer to [Unlicense](https://unlicense.org)
