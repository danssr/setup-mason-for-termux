# smason-for-termux
A bash script to set up packages for Neovim Mason in Termux. This script solves the 'current platform not supported' error when installing packages with Mason, specifically in Termux.

## How to Use

### Step 0: Ensure you have "which" installed on termux
```bash
pkg install which
```
### Step 1: Make the Script Executable
Set the executable permissions:

```bash
cd mason-for-termux
chmod +x install-in-mason
```

### Step 2: Run the Script
Now, you can use the script to install any package for Neovim Mason. For example:

```bash
./install-in-mason lua-language-server
./install-in-mason stylua
```

### Requirements
- Termux
- Neovim with Mason installed (Mason is automatically installed if you use LazyVim or any similar setup)
