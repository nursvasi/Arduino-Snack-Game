This code is an implementation of a snake game on an Arduino using an OLED display and a joystick. The Adafruit_SSD1306 and Adafruit_GFX libraries are used to control the OLED display, while the joystick is used to determine the direction of the snake. The screen size is 128x64 pixels, with an I2C address of 0x3C. The joystick is connected to pins 34 (X-axis), 35 (Y-axis), and 32 (button).

Initially, the setup() function initializes the OLED display, sets the joystick pins, and defines the starting positions for the snake and the food. The loop() function runs continuously while the game is active, reading joystick inputs, moving the snake, checking for collisions and food consumption, and updating the display. The joystick inputs determine the direction of the snake, and the snake moves accordingly. The program checks if the snake collides with itself, and if the snake eats the food, it increases the score, spawns new food, and grows the snake. Each cycle, the display is cleared, the snake and food are redrawn, and the score is displayed. When the game ends, a "Game Over!" message is shown.
![WhatsApp Image 2023-12-25 at 14 16 06](https://github.com/user-attachments/assets/51ee242c-49f7-4f0d-a733-cfad6a108be3)


![Uploading WhatsApp Image 2024-01-03 at 00.29.46.jpeg…]()
