# 🐍 Snake Water Gun Game

A Python implementation of the classic **Snake-Water-Gun** game — the South Asian version of Rock-Paper-Scissors. Play against the computer and test your luck!

---

## 🎮 How to Play

Snake-Water-Gun follows simple rules:

| Your Choice | Computer's Choice | Result |
|-------------|-------------------|--------|
| 🐍 Snake    | 💧 Water          | You Win (snake drinks water) |
| 🐍 Snake    | 🔫 Gun            | You Lose (gun kills snake) |
| 💧 Water    | 🔫 Gun            | You Win (water rusts gun) |
| 💧 Water    | 🐍 Snake          | You Lose (snake drinks water) |
| 🔫 Gun      | 🐍 Snake          | You Win (gun kills snake) |
| 🔫 Gun      | 💧 Water          | You Lose (water rusts gun) |
| Any         | Same              | Draw! |

---

## 🚀 Getting Started

### Prerequisites

- Python 3.x installed on your system
- No external libraries needed — uses only Python's built-in `random` module

### Run the Game

```bash
# Clone the repository
git clone https://github.com/your-username/snake-water-gun.git

# Navigate into the folder
cd snake-water-gun

# Run the game
python main.py
```

---

## 🕹️ How to Use

When prompted, enter one of the following:

| Input | Meaning |
|-------|---------|
| `s`   | 🐍 Snake |
| `w`   | 💧 Water |
| `g`   | 🔫 Gun   |

### Example

- Enter your choice: s

- You chose Snake

- Computer chose Water

- You Win!

## 📁 Project Structure 

snake-water-gun/

│

└── main.py       # Main game logic

---

## 🧠 How It Works

- The computer randomly picks Snake, Water, or Gun using Python's `random.choice()`
- The player enters their choice via keyboard input
- Both choices are mapped using dictionaries for clean, readable logic
- The winner is determined by comparing both values and printing the result

---

## 🛠️ Built With

- **Python 3** — Core language
- **random** — Built-in module for computer's random choice

---

## 👩‍💻 Author

**Ayesha**
