# install brew

https://brew.sh/

/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

```Bash
==> Next steps:
- Run these commands in your terminal to add Homebrew to your PATH:
    echo >> /Users/brian/.zprofile
    echo 'eval "$(/opt/homebrew/bin/brew shellenv zsh)"' >> /Users/brian/.zprofile
    eval "$(/opt/homebrew/bin/brew shellenv zsh)"
- Run brew help to get started
- Further documentation:
    https://docs.brew.sh
```

# Basic command

```Bash
# 搜尋套件
$ brew search <name>

# 安裝套件
$ brew install <name>

# 安裝清單
$ brew list

# 更新 Homebrew 本身（及獲取最新套件清單）
$ brew update

# 升級所有已安裝套件
$ brew upgrade

# 查看哪些套件有新版本
$ brew outdated

# 清理舊版本的安裝檔（釋放硬碟空間）
$ brew cleanup

# 檢查系統環境（會提示潛在問題與修復建議）
$ brew doctor

# 查看套件詳細資訊（如依賴關係、安裝路徑）
$ brew info <name>

# 常用
$ brew update && brew upgrade && brew cleanup

```

# Install Formulae

## git

```Bash
# Update Homebrew
brew update

# Install Git
brew install git

git --version
```

## tree

```Bash
# Update brew
brew update

# Install tree
brew install tree

# 在要顯示目錄的路徑下
tree
```

## remove

```Bash
# 顯示安裝清單
brew list -l

# 卸載軟體
brew uninstall <name>

# 清理不再需要的依賴套件 (Dependencies)
brew autoremove

# 清理下載的快取檔案 (Cache files)
brew cleanup
```


# Install Casks

```Bash
# 好用工具
brew install --cask raycast rectangle google-chrome


# 開發 IDE
$ brew install --cask pycharm
$ brew install --cask jetbrains-rider
$ brew install --cask visual-studio-code
$ brew install --cask postman

```

# Remove Casks

```Bash
# 如果你想用 Homebrew 卸載 app 並清乾淨所有暫存檔，建議使用
$ brew uninstall --cask --zap <name>

# Force uninstall and zap the application
$ brew uninstall --cask --zap --force <name>
```

-- Brewfile
brew bundle dump


brew bundle


