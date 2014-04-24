# Chat-GBH

  Chat-GHB is a simple chat that let's you see the how two clients comunicate with a server, the client is sending hello world to the server every second and the server is always listening, but this is boring, let's get to the real stuff...

## Installing

  To install Chat-GBH you just have to:

    - Download the project
    - Install python(https://www.python.org/)
    - Install virtualenv(http://www.virtualenv.org/en/latest/)

  Next on the command prompt or bash move inside the directory and activate the enviroment, you do so with:
    
    . chat/bin/activate

## Running

  Run the server:

    python server.py

  and open

    client.html

  in your browser.

  To activate debug output on the server:

    python server.py debug

  To run the Python client

    python client.py ws://127.0.0.1:9000

  To activate debug output on the client

    python client.py ws://127.0.0.1:9000 debug


