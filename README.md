# Simple Shell Cleaner

## What is it?
This is basically a shortcut command that does exactly the same as the clear command does in Linux; but with you having to type less, just the c word. It cleans the terminal.

## Available to

Linux

## How to Install

### Create (If it doesn't exist already) the .bash_aliases file on your home directory:
```
test -f ~/.bash_aliases && echo file already exists, please paste the next command. || touch ~/.bash_aliases
```
### Create a folder named c_programs inside your home directory:
```
test -d ~/c_programs && echo The folder already exists. Please, paste the next command. || mkdir ~/c_programs
```
### Clone the Simple Shell Cleaner inside the c_programs folder:
```
cd ~/c_programs
git clone https://github.com/cryswerton/simple-shell-cleaner.git
```
### Create an alias in your .bash_aliases file:
```
echo "alias c=\"~/c_programs/simple-shell-cleaner/c\"" >> ~/.bash_aliases
```
### Now just restart the terminal and it will work fine!


