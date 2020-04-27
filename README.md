# gamebrowser
Universal Game Browser

A simple card and board game platform to build an online card/board game more easy.

The browser is a web based game player. It will connect to the game server (currently using socket.io),
which provide chat and room capabilities, and also dynamic game selection.

Game rule are provided/defined in another "server", which is/are connected to the server as a client.

Browser has a basic function, such as draw tile/card, move card, detect click, display text, display button,
but all procedure are driven by server. Server receive all standard click from browser, and then ask the
game rule server to decide the next step.

Game server handle the chats and rooms stuff.
Rule handle by game rule server.
