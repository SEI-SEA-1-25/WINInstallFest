# Windows 10 OS

### SEI Seattle Windows Install Fest

### Part 1 

For the first portion of the class, we'll be working exclusively inside of the browser. We'll be installing the following tools.
Slack
VS Code
Git (Probably not)
Node.js
Postgres

### Slack

We will be using slack to communicate throughout the course. You should've received an invite to our channels via e-mail. You can login via the web browser, but downloading / installing the app is highly recommended.

​[Download Slack](https://slack.com/downloads/windows)

### Configuring GIT

Using your email credentials for GIT, run these commands with your user and email configured.

git config --global user.name "YOUR-USERNAME"
git config --global user.email "YOUR-EMAIL-ADDRESS"
git config --global push.default simple
git config --global credential.helper cache

Setting up SSH Key

You might find your self having to re-authenticate GIT every time you work on your command line. Setup SSH Keys to let Github remember your machine in the future.

    ​Github Generating SSH Keys​

Install VS Code

Currently the most popular editor according to developer polls. This is Microsoft's free version of Visual Studio.

Download and install VS Code from here​

You're all good to go now, but for ease of use, let's make it so we cna automatically open up any file or project in VS Code, from our command line. The following instructions are taken from these docs. If you're on a windows or linux, see the left-side menu to switch to the instructions for your machine.

To be able to open VS Code from any directory, open the Command Palette (Shift+⌘+P) and type 'shell command' to find the Shell Command: Install 'code' command in PATH command (it will be the first one that comes up).

Restart the terminal for the new $PATH value to take effect. You'll be able to type 'code .' in any folder to start editing files in that folder.

I think you should use an
`<addr>` element here instead.