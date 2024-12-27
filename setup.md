# Laptop Setup

This guide walks you through setting up your Windows computer for working on Python projects such as the Data Analysis Lab. It includes:

1. Installing Python
2. Setting up Anaconda for virtual environments
3. Installing Visual Studio Code (VS Code) as the Integrated Development Environment (IDE)
4. Installing Git for version control

---

## Prerequisites

- **Operating System (OS)**: Windows  
  This guide uses commands for Windows OS. If you are using a different OS (e.g., macOS or Linux), follow the same steps with adjustments for your system. You can modify the commands for macOS or Linux using resources such as ChatGPT or by consulting platform-specific documentation.
- **Stable Internet Connection**

---

## Step 1: Python Setup

#### 1. **Check if installed**:

Open Command Prompt (type `cmd`, and press Enter) and run:

```cmd
python --version
pip --version
```

If python already installed then skip to next section. If not, proceed with the steps below to install it.

#### 2. **Download execution file:**

- Visit the official website: [python website](https://www.python.org/downloads/)
- Locate a reliable version of Python 3. Choose the correct link for your device from the options provided: either Windows installer (64-bit) or Windows installer (32-bit).
- Click the download link for the installer corresponding to your system.

#### 3. **Install execution file:**

- Once the installer is downloaded, open the `.exe` file to start the installation process.
- On the installation screen, check the following options:
  - **Install launcher for all users:** This ensures the Python launcher is available to all users of the computer.
  - **Add Python to PATH:** This allows you to run Python from the command line easily.
- Click **Install Now** to proceed with the installation.

#### 4. **Verify successful installment:**

Open Command Prompt (type `cmd`, and press Enter) again and run:

```cmd
python --version
pip --version
```

This should display the installed Python and pip versions, confirming that Python has been successfully installed.

---

## Step 2: Annaconda Setup
#### 1. **Download execution file:**

- Visit the official website: [annaconda website](https://www.anaconda.com/download/success)
- Choose the correct link for your device from the options provided.
- Click the download link for the installer corresponding to your system.

#### 2. **Install execution file:**

- Once the installer is downloaded, open the `.exe` file to start the installation process.
- On the installation screen, check the following options:
  - Select the installation option: **Just Me (Recommended)**
  - keep destination folder as default.
  - Select **Add Anaconda3 to my PATH environment variable**.
- Click **Install Now** to proceed with the installation.

#### 4. **Verify successful installment:**

Access the CLI for your operating system:
1. Search for “Anaconda Prompt” in the taskbar search.
2. Select Anaconda Prompt.
   
You should see (base) in the command line prompt. This tells you that you’re in your base conda environment. To learn more about environments, see Environments.
Run any conda command. For example:
- `conda list` - Displays a list of packages installed in your active environment and their versions.
- `anaconda-navigator` - Opens Anaconda Navigator.

---

## Step 3: VS Code Setup
#### 1. **Download and install:**

- Visit the official website: [vs code website](https://code.visualstudio.com/download)
- Choose the correct link for your device from the options provided.
- Click the download link for the installer corresponding to your system.
- Once the installer is downloaded, open the `.exe` file to start the installation process. (keep everything in default)

#### 2. **Installing Essential VSCode Python Extensions:**
- Install [python extension](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
- Install [python indent extension](https://marketplace.visualstudio.com/items?itemName=KevinRose.vsc-python-indent)
- Install [jupyter extension](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)

---

## Step 4: Git and Github Setup

- Visit the official git website: [git website](https://git-scm.com/downloads)
- Visit the official github website: [github website](https://github.com/apps/desktop)
- Choose the correct link for your device from the options provided.
- Click the download link for the installer corresponding to your system.
- Once the installer is downloaded, open the `.exe` file to start the installation process by following the setup in this youtube video: [setup video](https://www.youtube.com/watch?v=cz6ubItv2SM&ab_channel=SalesforceMentor-Walters954)
  
For common commands in git: [git toturial](https://www.simplilearn.com/tutorials/git-tutorial)





