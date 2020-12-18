# chat-server-python
This is simple chat app on python3

import asyncio

from textwrap import dedent

In the first terminal, run the preceding code:

$ python my_server.py

And in the second terminal, connect to the server using nc

nc 127.0.0.1 8888

or telnet if you’re on Windows:

telnet 127.0.0.1 8888


• As a connected user, I may quit by sending the message
/quit.

• As a connected user, I may list all connected users by
sending the message /list.

• As a connected user, any text (excluding the mentioned
messages) that I send is broadcast to all connected
clients.
