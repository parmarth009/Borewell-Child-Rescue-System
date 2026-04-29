# Borewell-Child-Rescue-System
IoT-based Borewell Child Rescue System using Raspberry Pi Pico with real-time monitoring of temperature (LM35), gas levels (MQ-5), and GPS tracking (NEO-6M). Features a motorized gripper controlled via serial commands (1=grip, 2=release, 3=stop) using L298N, enabling safe and efficient rescue operations.
#  Borewell Child Rescue System (IoT)

An IoT-based rescue system designed to assist in borewell emergencies by monitoring environmental conditions and enabling remote-controlled gripping mechanisms.

##  Features
-  Temperature monitoring (LM35)
-  Gas detection (MQ-5)
-  GPS location tracking (NEO-6M)
-  Camera & microphone support
-  Motor control using L298N (Gripper system)
-  Laptop-based command interface (1 = Grip, 2 = Release, 3 = Stop)

##  Tech Stack
- Raspberry Pi Pico (MicroPython)
- Python (Serial Communication)
- Sensors: MQ-5, LM35, GPS NEO-6M
- Motor Driver: L298N


##  How to Run
1. Upload `pico_code.py` to Raspberry Pi Pico
2. Connect Pico via USB
3. Run `laptop_control.py`
4. Use commands:
   - `1` → Grip
   - `2` → Release
   - `3` → Stop
     
##  Demo Video
   https://www.youtube.com/watch?v=ZS7ubXPcYcU
   
##  Future Improvements
- GUI dashboard
- Live video streaming
- Emergency alert system
- GUI dashboard
- Live video streaming
- Emergency alert system
