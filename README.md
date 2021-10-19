# experiment with socket

This repo demonstrate a way to steam live video using socket.

Reference: [Sending live video frame over network in python opencv - Stack Overflow](https://stackoverflow.com/a/55432139/13044647)

## Run

### Windows

```bash
python .\socket-receiver.py
python .\socket-sender.py
```

### OS X & Linux

```bash
python3 .\socket-receiver.py
python3 .\socket-sender.py
```

## Installation of virtual environment

### Windows

```bash
# setup basic environment
python -m venv .venv

# activate virtual environment
.venv/Scripts/Activate.ps1

# fetch dependency
pip install -r requirements.txt
```

### OS X & Linux

```bash
# setup basic environment
python3 -m venv .venv

# activate virtual environment
source .venv/bin/activate

# fetch dependency
pip3 install -r requirements.txt
```