
## Programming examples

These are examples with specifications posted in this repository.
If you would like to try a pre-release version of the Beads compiler, visit us on [Discord](https://discord.gg/pTAdsSW), and let us know if you are mac or windows (sorry no linux yet), what kind of apps you would like to build, and how many years of experience you have.

Beads is not a minor rehash of Python or JS. It is a clean sheet design, carefully crafted to catch as many errors at compile time as possible so you spend less time debugging. These examples barely scratch the surface of the full range of Beads features, such as:

1. can run in reverse (AKA time-travel-debugging) 
2. automatic refresh of screen areas when the underlying model changes
3. protected arithmetic like Excel
4. units of measure like 3 m + 2 ft (even at runtime)
5. a proportional layout system that responds to size changes beautifully
6. greatly simplified regular expressions
7. a simple and flexible module system 
8. no make system needed for most projects

### Example: Chess

The classic board game. Complexity rating: 1500 words

![chess example](http://beadslang.com/projects/chess/screenshots/chess.png)

### Example: Tic-tac-toe client/server version

The classic board game, but in multiplayer form, where you can play or watch 12 different pairs of people playing across the internet, using TCP sockets. We write both the client and the server in Beads. The server publishes the game state, and the client subscribe to the published shared mutable state. Each of the players receives without any message handling code the updated state of the game. The clients make their moves by invoking remote function calls. You code the program as a standalone, then split the code into two parts. Client/server has never been so easy. No messy API's for message handling, all encoding and decoding is done automatically, and packets are sent in binary not JSON for maxiumum compactness and performance. A complexity rating of 1500 words.

![tictactoe example](http://beadslang.com/projects/tictactoe_net/docs/screenshot.png)

### Example: Tic-tac-toe game standalone version

The classic children's game, two player (no AI). Complexity rating: 520 words

![tictactoe example](http://magicmouse.com/beads/examples/TicTacToe/tictactoe.gif)

### Example: Color picker utility

A handy tool for programming; shows the HTML named colors, sorted in a convenient to use sort order. Approx. 1300 words.

![color picker](http://beadslang.com/projects/color_picker/docs/screenshot.jpg)

### Example: Bearsweeper game

The classic Minesweeper game, recast with a Bear in the starring role. Complexity rating: 1000 words

![bearsweeper example](http://magicmouse.com/beads/examples/bearsweeper/game1_small.png)

### Example: Lumberjack game

A very simple wood chopping game, built for little kids. A rewrite of an existing React/TS game that is can be run [here](https://lumber-jack.netlify.com/). We compare the two implementations to see how it differs in word count, number of dependencies, memory usage. Complexity rating: 750 words

![lumberjack example](http://magicmouse.com/beads/examples/lumberjack/lumberjack_screenshot.jpg)

### Example: Calculator

The classic Apple calculator program, except without the bugs that Apple has! Complexity rating: 500 words

![calculator example](http://magicmouse.com/beads/examples/calculator/calculator.gif)

### Example: Snake game

The classic snake game as popularized by Nokia cellphones. Probably the most fun per line of code ever made. Program complexity rating: 500 words.

![snake example](http://magicmouse.com/beads/examples/snake/snake_animated.gif)

### Example: Sort method contest

The classic bubble sorting algorithm is pitted against the just slightly more complicated but a zillion times faster Quicksort amethod. Watch the two side by side sort the same number list, and see why Quicksort is so much more clever, by moving things larger distances. The larger the sample size the more terrible the bubble sort works. Program complexity rating: 440 words.

![sort example](http://magicmouse.com/beads/examples/sort_contest/screenshot_bubble_400.png)

### Example: Wristwatch simulation

This simple program simulates a wristwatch. Program complexity rating: 180 words.

![watch example](http://magicmouse.com/beads/examples/watch/watch_example_animated.gif)

### Example: Analog clock

This simple program will draw a clock on the screen. This is among the shortest possible graphical programs one can imagine. Program complexity rating: 150 words.

![clock example](http://magicmouse.com/beads/examples/clock/clock_screenshot_anim.gif)

