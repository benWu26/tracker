# Costco Stock tracker

This will track the stock of a item on a Costco Website and will send an email alert if the specified item is in-stock or an error occurs.

*disclamer: These instructions are for macOS*

# Getting Started

## Clone the repository

Open your terminal

Navigate to certain directories(folders)

```bash
    cd /path/to/file
```

clone the repository using

```bash
    git clone https://github.com/benWu26/tracker.git
```

install git if needed

check if successfully cloned by running 

```bash
    ls
```

and you should see the file contents in your repo

## Install Python
Make sure you have python installed

Run these commands in your terminal:
```bash
    python3 --version
```

or 

```bash
    python --version
```

Install python here: https://www.python.org/downloads/

*Note: if python3 works use python3 for the rest of the commands*

## create virtual environment

run this in the terminal of the directory of the project:

```bash
    python -m venv myenv
    source myenv/bin/activate
```

## Install Dependencies

run this in the terminal of the directory of the project:

```bash
    pip install -r requirements.txt
```

## update the script

```bash
    vim tracker.py
```

Then use the arrow keys to navigate the file and then type in i to start to edit the file.

To then just change the 'msg','recipients', and 'link' in the file

Then click esc and type :wq

## create the .env file

```bash
    touch .env
```

then copy the file that I would have sent and copy it to the file

```bash
    vim .env
```

click i, then copy, and then quit using esc then :wq

## try the script

run this in the terminal:
```bash
    python tracker.py
```

# Automation of the script





