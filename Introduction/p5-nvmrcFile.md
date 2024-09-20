# .nvmrc File
>To "pin" a specific Node.js version for your project, you need to create a .nvmrc file in the root of your project directory. This file informs Node.js and the installed package manager on your system to utilize the specified Node version mentioned in the .nvmrc file.

>Follow the directions below to create and use the .nvmrc file:

1. Open a text editor in the root of your project directory.
2. Create a new file and save it as .nvmrc (including the leading dot).
3. In the .nvmrc file, specify the Node version you want to use for your project. You can find the desired version by visiting the official Node.js website and looking for the Long-Term Stable (LTS) or the latest version. For example, you can simply write v18.16.0 in the .nvmrc file.
4. Save the .nvmrc file and close the text editor.
>Once you have created the .nvmrc file with the desired Node version, you can use the following command to install and set that specific Node version for your project:
```
$ fnm use --version-file-strategy local
```
>This command will read the .nvmrc file in your project directory and install the specified Node version, ensuring that it is used for your project.

>Remember to always commit and share the .nvmrc file with your project collaborators, so everyone is using the same Node version.