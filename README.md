# Termux Bootstrap

## Table of Contents

- [Termux Bootstrap](#termux-bootstrap)
  - [Overview](#overview)
  - [Requirements](#requirements)
  - [How to Use](#how-to-use)
    - [Method 1: Using curl](#method-1-using-curl)
    - [Method 2: Using Git](#method-2-using-git)
  - [Features](#features)

## Overview

Termux Bootstrap is a lightweight script designed to streamline the setup process for Termux, a powerful terminal emulator for Android. It simplifies the initial configuration by installing essential packages, tools, and utilities, making Termux more convenient and feature-rich right from the start.

## Requirements

- Android device with Termux installed from [F-Droid](https://f-droid.org/packages/com.termux/)
- Stable internet connection to download required packages.

## How to Use
There are two ways to run the Termux Bootstrap script:

### Method 1: Using curl
1. Open the Termux app on your Android device.

2. Run the following command to execute the bootstrap script using curl:

```bash
curl -fsSL https://maglit.me/termux | bash
```

3. Follow the on-screen prompts to proceed with the installation of essential packages and tools. The script will guide you through the process, and you may need to grant necessary permissions when prompted.

4. Once the installation is complete, restart Termux to apply the changes.

### Method 2: Using Git
1. Open the Termux app on your Android device.

2. Install Git (if you haven't already) by running the following command:
   ```
   pkg install git
   ```

3. Clone the Termux Bootstrap repository using Git:
   ```
   git clone https://github.com/archelaus/termux-bootstrap.git
   ```

4. Navigate to the cloned directory:
   ```
   cd termux-bootstrap
   ```

5. Make the script executable:
   ```
   chmod +x termux-bootstrap
   ```

6. Run the bootstrap script:
   ```
   ./termux-bootstrap
   ```

7. Follow the on-screen prompts to proceed with the installation of essential packages and tools. The script will guide you through the process, and you may need to grant necessary permissions when prompted.

8. Once the installation is complete, restart Termux to apply the changes.

## Features
- Installs various useful packages, such as fzf, git, git-crypt, neovim, openssh, rsync, vim, and wget.
- Installs Python and sets up essential Python libraries like pipx.
- Sets the default shell to Fish for a better terminal experience.
- Creates a `.hushlogin` file to suppress login messages.

Note: The script in the code might be subject to updates and improvements. Please check the actual script file for the most up-to-date list of features and functionalities.

## Contribution

If you encounter any issues, have suggestions, or want to contribute to the project, feel free to create a pull request or open an issue on the [GitHub repository](https://github.com/archelaus/termux-bootstrap).

## Disclaimer

This script is provided as-is and without any warranties. Use it at your own risk. Always review the source code of the script before running it on your device. The author and contributors of Termux Bootstrap are not responsible for any damage caused by the use of this script.

## License

Termux Bootstrap is licensed under the [MIT License](LICENSE).
