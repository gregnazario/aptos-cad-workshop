# Aptos create-aptos-dapp Workshop

## Introduction

This workshop will guide you through the process of creating a decentralized application (dApp) using the Aptos
platform.

# Set up prerequisites

Overview:

1. Install Node.js
2. Install Python
3. Install Git
4. Set up a GitHub account
5. Clone the repository
6. Run create-aptos-dapp

Choose your operating system below:

- [Set up for macOS](#prerequisites-macos)
- [Set up for Windows](#prerequisites-windows)
- [Set up for Linux](#prerequisites-linux)

## Prerequisites: macOS

### Recommended: Install with Homebrew

- If you are using macOS, we strongly suggest you install Homebrew, a package manager for macOS. You can
  find [instructions to install it here](https://brew.sh/).
- Once that's done open a terminal with `⌘ Cmd + Space`, typing `terminal`, and pressing `Enter`.
- Then, you can simply run the following commands to install Node.js, Python, and Git:

```bash
brew install node
brew install python
brew install git 
```

#### Verify installation

To verify that you have installed Node.js, Python, and Git correctly, you can run the following commands in the same
terminal

```bash  
node --version
python --version
git --version
```

Afterward, you can proceed to setting up a [GitHub account](#set-up-a-github-account).

### Not recommended: Install Manually

#### 1. Install Node.js

To install Node.js, you can download the installer from the [official website](https://nodejs.org/en/download/).

#### 2. Install Python

To install Python, you can download the installer from the [official website](https://www.python.org/downloads/).

#### 3. Install Git

To install Git, you can download the installer from the [official website](https://git-scm.com/downloads).

#### Verify installation

Once that's done, open a terminal with `⌘ Cmd + Space`, typing `terminal`, and pressing `Enter`.

To verify that you have installed Node.js, Python, and Git correctly, you can run the following commands:

```bash
node --version
python --version
git --version
```

Afterward, you can proceed to setting up a [GitHub account](#set-up-a-github-account).

## Prerequisites: Windows

### Recommended: Install with Chocolatey

Using a package manager like [Chocolatey](https://chocolatey.org/), you can install Node.js, Python, and Git.

First, open a PowerShell window by pressing `⊞ Win + R`, typing `powershell`, and pressing `Enter`.

```powershell
choco install nodejs
choco install python
choco install git
```

#### Verify installation

To verify that you have installed Node.js, Python, and Git correctly, you can run the following commands in the same
PowerShell window:

```powershell
node --version
python --version
git --version
```

Afterward, you can proceed to setting up a [GitHub account](#set-up-a-github-account).

### Not recommended: Install Manually

#### 1. Install Node.js

To install Node.js, you can download the installer from the [official website](https://nodejs.org/en/download/).

#### 2. Install Python

To install Python, you can download the installer from the [official website](https://www.python.org/downloads/).

#### 3. Install Git

To install Git, you can download the installer from the [official website](https://git-scm.com/downloads).

#### Verify installation

First, open a PowerShell window by pressing `⊞ Win + R`, typing `powershell`, and pressing `Enter`.

To verify that you have installed Node.js, Python, and Git correctly, you can run the following commands:

```powershell 
node --version
python --version
git --version
```

Afterward, you can proceed to setting up a [GitHub account](#set-up-a-github-account).

## Prerequisites: Linux

### Recommended: Install with package manager

Using your package manager, you can install Node.js, Python, and Git. Here are some examples:

<details>
<summary>Install with <code>apt</code> (Ubuntu, Debian)</summary>
```bash
sudo apt install nodejs
sudo apt install python3
sudo apt install git
```

</details>

<details>
<summary>Install with <code>dnf</code> (Fedora)</summary>
```bash
sudo dnf install nodejs
sudo dnf install python3
sudo dnf install git
```
</details>

<details>
<summary>Install with <code>pacman</code> (Arch)</summary>
```bash
sudo pacman -S nodejs
sudo pacman -S python
sudo pacman -S git
```
</details>

<details>
<summary>Install with <code>zypper</code> (openSUSE)</summary>
```bash
sudo zypper install nodejs
sudo zypper install python3
sudo zypper install git
```
</details>

<details>
<summary>Install with <code>yum</code> (CentOS, AmazonLinux)</summary>
```bash
sudo yum install nodejs
sudo yum install python3
sudo yum install git
```
</details>

Afterward, you can proceed to setting up a [GitHub account](#set-up-a-github-account).

### Not recommended: Install Manually

### 1. Install Node.js

To install Node.js, you can download the installer from the [official website](https://nodejs.org/en/download/).

### 2. Install Python

To install Python, you can download the installer from the [official website](https://www.python.org/downloads/).

### 3. Install Git

To install Git, you can download the installer from the [official website](https://git-scm.com/downloads).

### Verify installation

To verify that you have installed Node.js, Python, and Git correctly, you can run the following commands:

```bash
node --version
python --version
git --version
```

Afterward, you can proceed to setting up a [GitHub account](#set-up-a-github-account).

## Set up a GitHub account

To get a copy of this repository, you will need to
have [set up a GitHub account](https://docs.github.com/en/get-started/start-your-journey/creating-an-account-on-github),
so we can set up a git repository for your project. If you already have one, login to it.

Once you have set up a GitHub account, you can proceed to [forking the repository](#fork-the-repository).

## Fork the repository

To get a copy of this repository, you will need to fork it. Click on the `Fork` button at the top right
of [this page](https://github.com/aptos-labs/aptos-cad-workshop).

## Clone the repository

To clone the repository, you will need to copy the URL of your forked repository. You can do this by clicking on the
`Code` button on your forked repository and copying the URL.

Then, open a terminal or command prompt as during installation earlier and run the following command:

```bash
git clone https://github.com/<GITHUB_USERNAME>/aptos-cad-workshop
```

Replace `<GITHUB_USERNAME>` with your GitHub username.

## Run create-aptos-dapp

To run the `create-aptos-dapp` script, you will need to navigate to the repository you just cloned. You can do this by
running the following command:

```bash
cd aptos-cad-workshop
```

Then, you can run the `create-aptos-dapp` script by running the following command:

```bash
npx create-aptos-dapp@latest
```