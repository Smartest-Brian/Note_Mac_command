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

# formulae

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
brew uninstall <formula_name>

# 清理不再需要的依賴套件 (Dependencies)
brew autoremove

# 清理下載的快取檔案 (Cache files)
brew cleanup
```


# Casks

```Bash
$ brew install --cask jetbrains-rider
```

```Bash
$ brew install --cask pycharm
```



brew bundle dump


