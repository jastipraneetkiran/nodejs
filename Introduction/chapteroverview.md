>Node works on many platforms and can be installed on each platform in several ways. This short precursory chapter covers best-practice setup of Node.js on macOS, Linux and Windows machines.

# Learning Objectives
>By the end of this chapter, you should be able to:

- Determine the best way to set up and use Node on various platforms.
- Understand what executables are installed.
- Explain how to manage multiple Node versions.

# How Not to Install Node
>Node.js is often installed using an operating system's official or unofficial package manager, such as apt-get on Debian/Ubuntu, Brew on macOS, or Chocolatey on Windows. However, it is strongly advised against using this method to install Node. Why? Well, there are a few reasons.

- First, package managers tend to fall behind the frequent release cycles of Node.js. This means that the versions available through package managers might not be up to date, potentially missing out on important features, bug fixes, and security patches.
- Second, the placement of binary and configuration files and folders is not standardized across different OS package managers. This lack of standardization can lead to compatibility issues and confusion when working with Node.js and its related tools.

>Another significant problem with installing Node.js via an OS package manager is the need to use sudo (a command that grants root privileges) on non-Windows systems when installing global modules with Node's package manager, (npm). Granting root privileges to the installation process of third-party libraries is not an ideal setup for a developer's machine and is considered poor security practice.

>An alternative option is to install Node directly from the official Node.js website. However, it's worth noting that on macOS and Linux, sudo is still required for installing global libraries.

>Whether you are using Windows, macOS, or Linux, we will introduce a better way to install Node using a version manager in the following sections. However, before moving on to the next sections, it is highly recommended to completely uninstall Node if it has been installed via an operating system package manager or directly from the website.