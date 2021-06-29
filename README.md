# Simple Shell Cleaner

## What is it?
This is basically a shortcut command that does exactly the same as the clear command does in Linux; but with you having to type less, just the c word. It cleans the terminal.

## Available to

Linux

## How to Install

### Create (If it doesn't exist already) the .bash_aliases file on your home directory:
```
touch ~/.bash_aliases
```
### Create a folder named c_programs inside your home directory:
```
mkdir ~/c_programs
```
### Clone the Simple Shell Cleaner inside the c_programs folder:
```
cd ~/c_programs
git clone https://github.com/cryswerton/simple-shell-cleaner.git
```
### get in the simple-shell-cleaner folder that is inside your c_programs folder:
```
cd ~/c_programs/simple-shell-clear
```
### Inside the simple-shell-cleaner folder, type the following and press Enter to get the current path:
```
pwd
```
### Add this line to your .bash_aliases file, but **DON'T** forget to replace the path below with your own path:
```
alias c="path"
```
### Now just restart the terminal and it will work fine!


