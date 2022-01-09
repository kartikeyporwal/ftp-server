# Sample FTP server using `twisted`

This repo contains a script [`ftp_server.py`](./ftp_server.py) that helps launch an FTP server

## Installation

```bash

# Create a virtual environment
python -m venv test_env

# Activate the virtual environment
source ./test_env/bin/activate

# Install the necessary packages
python -m pip install -r requirements.txt

# Run the script; make the directory and port changes as needed
python ftp_server.py


```


## ERROR

```

    twisted.internet.error.CannotListenError: Couldn't listen on 127.0.1.1:21: [Errno 13] Permission denied.

    Fix:
        Run the script with sudo or change the port from 21 to some other port

```