# Auto Git

A simple and efficient Bash script to automate and streamline common Git operations (switching branches, merging, and deleting branches) using an interactive interface with `fzf`.

## 🚀 Getting Started

These instructions will get you a copy of the project up and running on your local machine for daily use.

### 📋 Prerequisites

To run this script, you need to have the following tools installed in your terminal:

* **Git** - Version control system.
* **FZF** - Command-line fuzzy finder (essential for the interactive menus).

#### 🐧 Linux (Ubuntu/Debian)
```bash
sudo apt install git fzf

```

#### 🍏 MacOS

```bash
brew install fzf

```

#### 🪟 Windows (Git Bash)

If you are using Git Bash, the best way to install is by cloning the official repository (just like in the course):

```bash
git clone --depth 1 [https://github.com/junegunn/fzf.git](https://github.com/junegunn/fzf.git) ~/.fzf
~/.fzf/install

```

> **Tip:** Answer **"y"** (yes) to all questions during installation to enable auto-completion and key bindings. Restart your terminal after finishing.

### 🔧 Installation

Follow the steps below to install and configure `auto-git` in your environment.

1. Clone the repository or download the `auto-git.sh` file:

```bash
git clone [https://github.com/matheusnakagaki/auto-git.git](https://github.com/matheusnakagaki/auto-git.git)

```

2. Make the script executable:

```bash
chmod +x auto-git.sh

```

3. (Optional) Move it to a folder in your PATH to run it from anywhere (e.g., `~/.local/bin`):

```bash
mkdir -p ~/.local/bin
cp auto-git.sh ~/.local/bin/auto-git

```

## ⚙️ Usage

Simply type `auto-git` in your terminal (if you configured the PATH) or run the script directly:

```bash
./auto-git.sh

```

The script will validate if you are inside a Git repository and open an interactive menu with the following options:

* **1 - Switch Branch:** Select and switch branches with a log preview.
* **2 - Merge Branch:** Select a branch to merge into the current one, with a diff preview.
* **3 - Delete Branch:** Select and delete a local branch.
* **4 - Exit:** Exit the program.

## 🛠️ Built With

* [Bash](https://www.gnu.org/software/bash/) - The scripting language used.
* [FZF](https://github.com/junegunn/fzf) - Tool used to create the interactive menus and previews.
* [Git](https://git-scm.com/) - The base tool for version control operations.

## ✒️ Authors

* **Matheus Nakagaki** - *Initial Work* - [matheusnakagaki](https://www.google.com/search?q=https://github.com/matheusnakagaki)

## 📄 License

This project is licensed under the GPL-3.0 License - see the [LICENSE](https://www.google.com/search?q=LICENSE) file for details.

## 🎁 Acknowledgments

* Thanks to the Git & GitHub course instructor for the inspiration.
* Thanks to the Open Source community for the amazing tools.
