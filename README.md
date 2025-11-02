# CodeBundler

A simple and powerful C# command-line tool for merging multiple source code files into one clean, organized file.

## 🚀 Overview

**CodeBundler** helps developers quickly combine code files from a selected directory into a single bundled file.  
You can choose the programming language, remove empty lines, add file origin comments, include author details, and more.

Ideal for organizing projects, sharing examples, or preparing documentation.

---

## ⚙️ Features

- 🧩 Merge all code files of a specific language (e.g. `.cs`, `.java`, `.py`)
- 📝 Optionally include the original file path as a comment
- 🔤 Add author information at the top of the bundle
- ⚙️ Sort files by name or type
- 🚫 Remove empty lines for cleaner output
- 🧠 Supports interactive command generation via `.rsp` files

---

## 🧰 Requirements

- .NET 6 or higher

---

## 🧑‍💻 Installation

```bash
git clone https://github.com/your-username/CodeBundler.git
cd CodeBundler
dotnet build
