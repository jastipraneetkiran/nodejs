# Creating NPM Shell Commands
Repeating frequently used shell commands can become laborious, especially when working with the terminal on a regular basis. However, we can alleviate this burden by creating custom Node Package Manager (NPM) shell commands. These commands are defined within the package.json file, specifically under the scripts object.

To create a custom NPM shell command, add the following lines to the scripts object in your package.json file:
```
"scripts": {
    "static": "serve -p 5050 static",
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  ```
In the above example, we have defined two shell commands: static and test.

The static command executes serve -p 5050 static, which starts the file server on port 5050.
The test command echoes an error message.
Use the npm run command, followed by the script name, to execute these commands in the terminal. For instance:
```
$ npm run static
```
By running npm run static, the defined static script will be executed, which will  start the file server for you.

This recommended practice of creating NPM shell commands reduces the repetitiveness of entering long and complex shell commands. As we progress through this course, we will utilize more of these shell commands to enhance our workflow.


