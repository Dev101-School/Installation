# Installation

#  How to install MinGW in local machine.

```js
1. download : [cpp] https://drive.google.com/folderview?id=1AfWvx6tOGN6WvZ_mzeUyvrWHU6kRUPc1
2. Extract the download folder into C drive.
3. Copy the path of MinGW bin.  
    example : C:\MinGW\bin
4. Set the environment variables
     4.1 Open the Start Search, type in “env”, and choose “Edit the system environment variables”:
     4.2 Click the “Environment Variables…” button.
     4.3 Select the Path and click the "edit" button.
     4.4 then add the "path of MinGW/bin" [C:\MinGW\bin]
     4.5 then save [OK][OK]

5. Restart your computer or your machine.
6. Open cmd
    6.1 Run g++ -v or gcc -v.
    6.2 if step number 6.1 working it's means All Done :)

```

# How to run .cpp in local machine.
 ```js

  1. g++ filename.cpp 
  2. ./a.exe

  1-linker-cmd:
  g++ filename.cpp && ./a.exe < input.txt > output.txt
  
```

# How to install gitbash in local machine.

```js
1. Download the Git Bash setup from the official website: ["https://git-scm.com/"]
2. Download the installer.
3. Run the [.exe] file you just downloaded and follow the instructions in the installer.​
4. Run Git Bash by right-clicking on any folder and selecting the Git Bash Here option from the context menu(right-click menu).

```
[for more details](https://phoenixnap.com/kb/how-to-install-git-windows)


# How to Setup Github account in local Machine

## Configure GitHub Credentials
```js
   1. Open gitbash or any terminal and run following commands
   2. git config ––global user.name “your username”
   3. git config ––global user.email “email_address”
   4. And Follow [Git Steps]["Agar repo phele bar create krte ho toh or" "Agar repo phele se hai toh"];
   5. set the password.
   6. Enjoy :)
```


# Git Steps

## Agar repo phele bar create krte ho toh  

```js
1. git init 
2. git add .
3. git status
4. git commit -m"message"
5. git branch -M main
6. git remote add origin URL
7. git push -u origin main

```

## Agar repo phele se hai toh  

```js
1. git add .
2. git status [option]
3. git commit -m"message"
4. git push
```

## Happy Coding







