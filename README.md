# The Linux Cheat Sheet

This repository contains some linux commands and shortcuts which may make your work with linux more efficient. Feel free to create issues if some don't work of if some information is incorrect. Also feel free to share this so people can learn more about the efficiency of linux and learn some shortcuts that may help them in their work. 

# INDEX:
<ol>
    <li class="indexvals"><a href="#bash-cheats">Bash Cheats</a></li> 
            <ul>
            <li class="indexvals"><a href="#bash-keybinds">Bash Keybinds</a></li>
            <li class="indexvals"><a href="#bash-command-control">Bash Command Control</a></li>
            </ul>
    <li class="indexvals"><a href="#zsh-cheats">Zsh Cheats</a></li>
            <ul>
            <li class="indexvals"><a href="#zsh-keybinds">Zsh Keybinds</a></li>
            <li class="indexvals"><a href="#zsh-control">Zsh Control</a></li>
            </ul>    
</ol>


## Bash Cheats

### Bash Keybinds

1. `ctrl+c` stops any command from running

- Example:

![image](https://user-images.githubusercontent.com/51316255/176604602-ac3b35d7-9df3-4c13-ad38-bf4bf490dbcd.png)

2. `ctrl+r` to search for a command used in the past

- Example:

![image](https://user-images.githubusercontent.com/51316255/176599581-224b3711-fed6-4bd2-97cd-811fe468d28f.png)

![image](https://user-images.githubusercontent.com/51316255/176599797-2dd59db1-a8f3-4122-8640-5f7b1bebd3e7.png)

3. `ctrl+a` to go  to the start of the line of the command
4. `ctrl+e` to go to the end of the line of the command
5. `ctrl+left arrow key` OR `ctrl+right arrow key` to go left and right of letter bunches. Skipping all characters except spaces. basically to go from the end of a command to the start of the command in one keybind

- Example: 

https://user-images.githubusercontent.com/51316255/176603118-df5e40f1-dc64-427a-87a3-86b32f1aaad7.mp4

6. `ctrl+L` to clear the terminal screen. Only inserts blank spaces for the screen itself. Scrolling up will show you the previous commands you have done  but it does clear the screen in a way

7. `ctrl+k` AND `ctrl+u` to cut/delete everything to the end of the line. This is very useful when using `nano` (the terminal text editor).

- Example:

https://user-images.githubusercontent.com/51316255/176654693-956dd3eb-8b09-404d-b5a6-2ec0999decff.mp4





### Bash Command Control

1. `!!` to run the last command
2. `sudo !!` to run the last command with superuser priveledges. This can save time if you forget to write sudo before a command as usually users use the left arrow key to go to the start of the command to type sudo. You can also use `ctrl+a` to go to the start of the line to add sudo to it if you do not with to use this command

- Example:

![image](https://user-images.githubusercontent.com/51316255/176601444-13aa3f93-7d81-451e-ae5f-94651e45e6d0.png)

3. `!pw` to run a command starting with the letters "pw". Replace the string after the exclamation mark `!` with something similar to the command you have run previously in your history and it will execute. Otherwise there will be an error `event not found`.

4. Example:

![image](https://user-images.githubusercontent.com/51316255/176787899-36b82c74-eea1-4737-9f8d-37f282f7f5b4.png)

![image](https://user-images.githubusercontent.com/51316255/176787925-6267d6ad-6d20-4a1c-acca-868d28b181df.png)



## Zsh Cheats

### Zsh Control

1. In Zsh you can instantly enter a directory by just typing the relative (`Documents/fastmap`) or full path (`/home/fluffy/Documents/fastmap`) of the desired directory to enter.

- Example:

https://user-images.githubusercontent.com/51316255/176688718-5bf0d552-853c-412f-8e46-458ed6b09ca3.mp4


### Zsh Keybinds

