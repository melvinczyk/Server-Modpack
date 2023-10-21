# Server-Modpack
This is my Minecraft Server modpack that I will update for my friends when they connect to my server


# How to get modpack from GitHub -> Local

This is a tutorial on how to use `git` to update the modpack and how to firstly get it onto your computer to use.

### How to download `git` (windows os)

If you do not have `git` installed than you need to go to this link [here](https://git-scm.com/downloads) and the website should look like this:

![Download page](https://phoenixnap.com/kb/wp-content/uploads/2021/04/download-git-for-windows.png)

Next you need to click `windows` and the screen should look like this and then download the *STANDALONE* version for your computer:

![Windows architecture](https://www.how2shout.com/wp-content/uploads/2022/09/Download-Git-for-Windows-11-or-10.png)

***IMPORTANT:*** To choose the correct version you need to know which version of windows you are operating. You can check that by doing going [here](https://support.microsoft.com/en-us/windows/which-version-of-windows-operating-system-am-i-running-628bec99-476a-2c13-5296-9dd081cdd808) and click the button that says `Open About settings`:

If that didn't work you can do this operation to get there:

Select: *Start*(the windows looking button)  > *Settings*(gear)  > *System*(square)  > *About*(i looking button)

**Next** Look for *Device specifications* > *System type* and it should tell you if you are running *32-bit* or *64-bit*.


### Finish Installing

Go to where you downloaded the file and there should be an executable that looks like this:

![Alt text](https://phoenixnap.com/kb/wp-content/uploads/2021/04/location-git-windows-download.png)

Just double click it and keep clicking `Next` until it gets to 
**Adjusting your PATH environment** where you need to select the **MIDDLE** option *Windows command Prompt*:

![Alt text](https://www.develves.net/blogs/asd/images/git-2.13.2-install/05-PATH.PNG)

Keep clicking `Next` until you get to `Finish`.


## Getting the Modpack

Open *Git Bash*

It should look something like this:

![Alt text](https://phoenixnap.com/kb/wp-content/uploads/2021/04/start-git-bash-windows.png)


![Alt text](https://www.how2shout.com/wp-content/uploads/2022/10/Git-Bash-Windows.png)

Go to the **GREEN CODE BUTTON** on my github and click it and copy the **HTTPS URL**

![Alt text](https://docs.github.com/assets/cb-32892/mw-1440/images/help/repository/code-button.webp)

**NEXT GO BACK TO THE GIT BASH AND TYPE THIS**

`cd Desktop`

This is where the modpack will be downloaded to. If you do not want it here you can change it to downloads like this:

`cd Downloads`

**NEXT TYPE THIS TO ACTUALLY CLONE THE MODPACK ONTO YOUR COMPUTER**

`git clone https://github.com/melvinczyk/Server-Modpack.git`

## Congrats you got the modpack onto your computer

The modpack should show up on curseforge even without you needing to *create a custom profile*. And if it does not load in a couple minutes check and see if you typed in the correct path when you typed:

>`cd ~\minecraft\Instances`

## Updating

