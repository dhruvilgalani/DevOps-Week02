# DevOps-Week02

A hands-on Git & GitHub collaboration exercise simulating a Junior DevOps Engineer's workflow — managing source code across feature branches, resolving merge conflicts, and integrating changes via Pull Requests.

## 📋 Project Overview

This repository demonstrates a realistic team-based Git workflow, including:
- Multiple contributors working on isolated feature branches
- Merging changes into `main` via Pull Requests
- Resolving a real merge conflict
- Maintaining clean, documented project structure

## 📁 Project Structure

```
DevOps-Week02/
├── app.py             # Backend sample logic
├── script.js          # Frontend sample logic
├── style.css          # Basic styling
├── requirements.txt   # Python dependencies
├── notes.txt          # Project notes
└── README.md          # Project documentation
```

## 🌿 Branches Used

| Branch | Purpose |
|---|---|
| `main` | Stable, production-ready code |
| `feature-backend` | Backend logic changes (`app.py`) |
| `feature-frontend` | Frontend logic changes (`script.js`) |

## 🚀 Getting Started

```bash
git clone https://github.com/yourusername/DevOps-Week02.git
cd DevOps-Week02
python app.py
```

## 🔀 Workflow Summary

1. Created two feature branches off `main`
2. Made independent changes on each
3. Opened Pull Requests for both branches
4. Merged `feature-backend` and `feature-frontend` into `main`
5. Resolved one merge conflict encountered during integration

## 🤝 Contributing

1. Create a feature branch: `git checkout -b feature/your-feature`
2. Commit your changes with a clear message
3. Push and open a Pull Request against `main`
4. Address review feedback before merging

## 📄 License

Educational project — part of DevOps Internship, Week 02 hands-on activity.
