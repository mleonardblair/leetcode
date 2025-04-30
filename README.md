
# leetcode Monorepo 🚀

Welcome to my **LeetCode monorepo**! This repository contains my solutions to various LeetCode problems, organized by topic and category. The repo uses **Git submodules** to organize problems within their respective categories.

## 📑 Table of Contents
- [Description](#description)
- [Repository Structure](#repository-structure)
- [LeetCode Profile](#leetcode-profile)
- [License](#license)

## 📝 Description
This repository consolidates my solutions to LeetCode problems. The solutions are organized by category using **Git submodules** to keep each category independent and well-structured. The categories include topic(s) like:
- **Dynamic Programming** 💡
- and more!

### Why Use Submodules? 🤔
Git submodules are used to organize different sets of problems into their own dedicated directories while still being part of the overall repository. This allows for a clean structure and makes it easier to track solutions across different topics.

## 📂 Repository Structure
The repository structure follows a monorepo pattern with nested submodules. Here's how the repo is organized:

```
leetcode/
│
├── dynamic-programming/               # Submodule: Dynamic Programming solutions
│   └── climbing-stairs/              # Sub-submodule: Climbing Stairs problem
│       ├── climbing_stairs.py
│       └── README.md
│   ├── TBD/
│   └── README.md
│
├── TBD/
│   ├── TBD/
│   └── README.md
└── README.md
```

- **Main Repository**: The `LeetCode-Solutions` root folder contains submodules for different topics (e.g., **Dynamic Programming**, **Arrays**, **Linked Lists**).
- **Submodules**: Each topic folder (like `dynamic-programming`) is a **Git submodule** that contains problems related to that topic.
- **Nested Submodules**: Some problems might also have their own submodules for further breakdown, like `climbing-stairs` inside `dynamic-programming`.

## 👾 LeetCode Profile
You can find my LeetCode profile here: [My LeetCode Profile](https://leetcode.com/mleonardblair/)

This link will take you to my **public profile**, where you can track my progress and review my problem-solving approaches. 🚀

## 🛡️ License
This repository is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.

---

Happy coding! 😊💻
