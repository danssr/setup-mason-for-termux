# setup-mason-for-termux
A bash script to set up packages for Neovim Mason in Termux. This script solves the 'current platform not supported' error when installing packages with Mason, specifically in Termux.

## How to Use

### Step 1: Clone the Repository Directly to `/usr/local/bin`
Run the following command to clone the script directly into `/usr/local/bin`, making it immediately usable:

```bash
git clone --depth=1 https://github.com/Amirulmuuminin/mason-package-setup.git /usr/local/bin/mason-package-setup
```

### Step 2: Make the Script Executable
Set the executable permissions:

```bash
chmod +x /usr/local/bin/mason-package-setup/install-in-mason.sh
```

### Step 3: Run the Script
Now, you can use the script to install any package for Neovim Mason. For example:

```bash
install-in-mason lua-language-server
```

### Requirements
- Termux with `apk` as the package manager
- Neovim with Mason installed
