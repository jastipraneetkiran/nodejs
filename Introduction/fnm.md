# Installing Node.js using FNM
>In this section, we will learn how to install Node.js on our system using a Node version manager called fnm (Fast Node Manager). This method is suitable for Windows, macOS, and Linux installations. While more information about installing Node.js can be found from our system's native sources, we recommend using fnm for a streamlined installation process.

>fnm is a fast and simple Node.js version manager that allows us to manage multiple released Node.js versions. It provides operations like installation, uninstallation, and automatic switching of Node versions based on the current directory. fnm supports cross-platform compatibility (macOS, Windows, Linux) and works with popular shells such as Bash, Zsh, Fish, PowerShell, and the Windows Command Line Prompt. It is designed for speed and offers compatibility with .node-version and .nvmrc files, making it an ideal choice for our needs.

>For full details and documentation, refer to the fnm GitHub repository: https://github.com/Schniz/fnm.

>To begin, we will install fnm and then use it to install Node. If you have curl installed, use the following command to install fnm using the install script:
```
$ curl -fsSL ht‌tps://fnm.vercel.app/install | bash
```
>If you do not have curl installed, you can manually download the script from the provided URL and execute it; or if you prefer a manual installation method or need more information, please visit the fnm repository page.

>Additionally, you can find instructions for setting up auto-completions for the terminal you’re using in the fnm repository page.

>After the installation, verify that fnm is working correctly by running the following command:

```
$ fnm --version
```
>The expected output should be fnm 1.33.1. If this command fails on Linux, try restarting the terminal by closing and reopening it or the SSH session and then running the command again. For troubleshooting information, refer to the original repository.


> If, upon restarting the terminal, you encounter a **"Command 'fnm' not found"** error, it is likely that the **$PATH** for the **fnm** executable was not properly set during the installation process. You can easily set it by entering the following command in the terminal:

```
$ export PATH="$HOME/.local/share/fnm:$PATH"
```
>With the version manager successfully installed, let's proceed to install the specific Node version we'll be using for this course:

```
$ fnm install --lts
```
>This command will install the latest LTS (Long-Term Support) version of Node.

>[!Important]
>It is important to note that the exact numbers at the end of the version may vary, however it would still be suitable for this course. For example, you can install the latest available version of Node by supplying the following command to fnm:

```
$ fnm install --latest
```
>To verify that Node is installed and check its version, use the following command:
```
$ node -v
```
>Congratulations! You now have the proper setup on your macOS or Linux machine to proceed with the course.

