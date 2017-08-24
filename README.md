# Sagitta: Endless Runner
An infinite, networked runner in C++. 

## Build the client
On unix-like systems, call `make` from the source directory. You will need the ncurses library and C++11 support on your system.

## Build the server
On unix-like systems, call `make server` from the source directory.

## Client Usage
Call `./runner [ <ip> <port> ]` from the binaries/runner directory.

## Server Usage
Call `./server [ <port> ]` from the binaries/server directory.

## How to Play
To play, you need to have two players. Player 1 (the first client to connect) controls the Y axis of the ship and controls the shooting. Player 2 (the second client to connect) controls the X axis of the ship.

The game goes "forever" as long as the players don't crash. It's an infinite runner game.
