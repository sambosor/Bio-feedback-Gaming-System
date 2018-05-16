# Bio-feedback-Gaming-System
Video Game on Nexys 4 DDR

The current bit file was meant to run with Nexys 4 DDR. 

Controller should be a USB keyboard. 

Movement is controlled by the arrow keys and shoot is controlled by the 'X' key. 

Reset the game by pressing button N17

Audio can be played by plugging speaker into mono audio out of Nexys 4 DDR

Pulse Sensor must be plugged into the XADC port (top row)

To play the game without the influence of the pulse sensor, turn sw<15> down.

BPM >= 80: Enemy shoots more projectiles

BPM >= 90: Meteors begin to fall

BPM >= 110: Player cannot shoot

BPM >= 140: Player dies.
