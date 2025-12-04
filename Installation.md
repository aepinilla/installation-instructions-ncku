# Workshop on AI Agents for Data Visualization

## Initial setup

1. Install the software:
- Windsurf [https://windsurf.com/]
- GitHub Desktop [https://desktop.github.com/download/]
- Miro [https://miro.com/apps/]

2. Create an account in the following sites:
- Kaggle [https://www.kaggle.com/]
- GitHub [https://github.com/]
- OpenAI API Platform [https://platform.openai.com]

3. Generate an API key in OpenAI API Platform.

## macOS Installation

Open the Terminal and enter the following commands

1. **Install Homebrew (if not already installed)**

   ```bash
   /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
   ```

2. **Install Python 3.11**

   ```bash
   brew install python@3.11
   ```

3. **Install uv package manager**

   ```bash
   brew install astral-sh/tap/uv
   ```

## Windows Installation

1. **Install GitBash: https://git-scm.com/install/windows with the default options**

2. **Open a PowerShell with Admin rights (click on "Run as Administrator").**

3. ** In the PowerShell window, run the following command to install Chocolatey (if not already installed)**

   ```powershell
   # Run in an Administrator PowerShell
   Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
   ```

4. **Install Python 3.11**

   ```powershell
   choco install python311 -y
   ```

5. **Install uv package manager**

   ```powershell
   pip install uv
   ```
