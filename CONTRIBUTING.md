# 🤝 Contributing to Snake Water Gun Game

First of all, thank you for taking the time to contribute! Every contribution — big or small — is appreciated and helps make this project better. 🎉

---

## 📋 Table of Contents

- [How Can I Contribute?](#how-can-i-contribute)
- [Getting Started](#getting-started)
- [Making Changes](#making-changes)
- [Submitting a Pull Request](#submitting-a-pull-request)
- [Code Style Guidelines](#code-style-guidelines)
- [Ideas for Contribution](#ideas-for-contribution)

---

## 💡 How Can I Contribute?

You can contribute in many ways:

- 🐛 **Report a bug** — Found something broken? Open an issue!
- ✨ **Suggest a feature** — Have a cool idea? We'd love to hear it!
- 🛠️ **Fix a bug** — Pick an open issue and submit a fix
- 📝 **Improve documentation** — Better README, comments, or guides
- 🎮 **Add new features** — Score tracking, replay option, difficulty levels, etc.

---

## 🚀 Getting Started

### 1. Fork the Repository

Click the **Fork** button at the top right of this page to create your own copy.

### 2. Clone Your Fork

```bash
git clone https://github.com/your-username/snake-water-gun.git
cd snake-water-gun
```

### 3. Create a New Branch

Always create a new branch for your changes — never work directly on `main`:

```bash
git checkout -b feature/your-feature-name
```

**Branch naming examples:**
- `feature/score-tracker`
- `fix/draw-condition-bug`
- `docs/update-readme`

---

## ✏️ Making Changes

- Make your changes in the new branch
- Test your code thoroughly before committing
- Keep your commits small and focused — one change per commit

```bash
git add .
git commit -m "Add: score tracking feature"
```

**Commit message format:**
| Prefix | When to use |
|--------|-------------|
| `Add:` | New feature added |
| `Fix:` | Bug fixed |
| `Update:` | Existing feature improved |
| `Docs:` | Documentation changes |
| `Refactor:` | Code cleanup, no feature change |

---

## 📬 Submitting a Pull Request

### 1. Push Your Branch

```bash
git push origin feature/your-feature-name
```

### 2. Open a Pull Request

- Go to the original repository on GitHub
- Click **"Compare & pull request"**
- Fill in the PR description:
  - What changes did you make?
  - Why did you make them?
  - Any screenshots or examples?

### 3. Wait for Review

Your PR will be reviewed as soon as possible. You may be asked to make some changes — that's completely normal! 😊

---

## 🎨 Code Style Guidelines

Please follow these simple rules to keep the code clean:

- Use **meaningful variable names** — `player_choice` not `pc`
- Add **comments** where logic is not obvious
- Keep functions **short and focused**
- Follow **PEP 8** Python style guide
- Test your code before submitting

**Example of clean code:**
```python
# Good ✅
player_choice = input("Enter your choice (s/w/g): ")

# Avoid ❌
x = input("Enter: ")
```

---

## 🎮 Ideas for Contribution

Not sure where to start? Here are some ideas:

- [ ] Add a **score tracker** — keep count of wins, losses, draws
- [ ] Add a **replay option** — ask player if they want to play again
- [ ] Add **input validation** — handle invalid inputs gracefully
- [ ] Add **difficulty levels** — easy, medium, hard mode
- [ ] Create a **GUI version** using Tkinter
- [ ] Add **color output** using colorama library
- [ ] Write **unit tests** for game logic

---

## ❓ Questions?

If you have any questions, feel free to open an **Issue** on GitHub and label it as `question`. I'll get back to you as soon as possible!

---

## 👩‍💻 Author

**Ayesha**

---

Thank you for contributing! Happy coding! 🚀
