# Resident-Evil-2-HealthBar-for-DualShock4
Python based script that changes LED color of your Dualshock4 controller while playing Resident Evil 2 Dualshock Ver. on Duckstation Emulator. Script check emulator shared memory values, and changes your LED color, dependign on your Health

Duckstation Settings:

- You need to enable Shared Memory:
Duckstation -> Settings -> Advanced -> Enable Shared Memory
Othervise script will not work.

- Duckstation Controller Settings
	• Enable SDL Input Source - On
	• SDL Dualshock Enhanced Mode - On

	• Controller Type - Digital controller (this will prevent vibration, because if you select Analog Controller, vibration will be enabled and it will interfeere with Controlled LED on every time a vibration is triggered). Currently there is no solution for this, so right now you can play only without vibration, and you won’t expirience flashing blue color every time controller vibrates.

General Setup
- Connect your controller to PC
- Run Duckstation
- Run the .exe

Functionality
- Leon A/B, Claire A/B full support of 5 possible colors:
Green, Yellow, Orange, Red, Purple (poison)

Ada/Sherry health was not implemented yet (maybe in future)


