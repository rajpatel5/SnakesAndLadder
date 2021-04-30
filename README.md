# Snakes and Ladder

This assignment was assigned by the B58 (Computer Hardware) course instructor at the University of Toronto. This project was created by a team of four. This project is a simple, yet highly interactive and fun snakes and ladder's game. The game has a dice which rolls from 1 to 6, the player on the screen moves based on the dice value. If the player rolls a 6 they get to roll again! The player positions can be viewed on the screen as well as on the DE2 board. When a player wins, the winner is displayed on the board along with a pattern of flashing led lights. 

This was coded in Verilog and was complied using Quartus. The dice uses a counter, clock and a rate divider; the counter counts from 1 to 6, and the clock and rate divider give it a rolling effect on the DE2 board. When the user let's go of the key, whatever number is displayed, that's the number the user rolled. The player movements work using two nested counters to draw the players on their corresponding positions and a look up table is used to keep track of the positions of the snakes and ladders. The flashing leds also use a clock and rate divider to display a unique, fun pattern. The code is bug free and the graphics is top-notch, atleast in terms of hardware standards. It is a 320 by 240 image, a higher resolution image was not possible because of limited memory on the board.
