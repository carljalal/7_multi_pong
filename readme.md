# similar to:
1) ping pong
2) RTS
3) brain game -- multitasking, attention, timing memory

# basic idea:
1) got balls
2) got paddles
3) got a "backboard"
4) got "sidewalls"
5) got a "lose" zone
6) got grid marks
7) got a camera (to move around board)

# options:
1) can draw variable number of balls
2) can draw variable number of paddles
3) can draw variable board depth
4) can draw variable board width
5) can draw color ball-paddle match requirements
6) can set variable ball speed
7) can set variable paddle speed
8) can lock/unlock mouse pointer to canvas for scrolling

# interface:
1) canvas for board
2) text with basic instructions
3) text with scoreboard and other metrics
4) textbox for board width
5) textbox for board depth
6) radio buttons for click-modes
7) button for clear balls and paddles
8) radio buttons for color
9) slider for speed

# click modes:
1) click to add ball
2) click to add paddle
3) click to start drawing wall
4) click to start drawing lose area
5) click to start drawing goal area
6) click to remove element

# internal data:
1) list of all elements
2) list of paddles
3) list of balls
4) list of walls
5) list of goal areas
6) list of lose areas
7) timer
8) score
9) [diagnostic] count of elements, balls, walls, goal areas, lose areas, paddles
10) ball speed
11) paddle speed
12) canvas mouse confinement lock

# functions:
1) [each] add element
2) [each] modify settings
3) scroll board
4) update ball/paddle positions
5) click-find-intersect element
6) remove element
7) ball/paddle collision updates

# later additions:
1) positional sound for ball movements
2) 3d support
3) word-paddles and word-balls

# future game ideas:
1) similar to lumosity fruit logic but with 2d or 3d rules
3) "name the preposition" training
4) visual color math count training
5) key-gate maze