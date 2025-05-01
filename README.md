🔧 Bluetooth-Controlled Wheelchair using Arduino

This project is a Bluetooth-controlled smart wheelchair developed using Arduino Uno and HC-05 Bluetooth module. The wheelchair can be wirelessly controlled via a mobile app using Bluetooth communication, offering a low-cost solution to enhance mobility assistance.

📌 Features

Remote control using Bluetooth

Easy-to-use mobile interface

Low-cost components

Responsive motor control using gear motors and motor driver

Portable, powered by lithium-ion batteries

🧰 Components Used

Arduino Uno -1
HC-05 Bluetooth Module-1
Lithium-Ion Battery (4V)-3
Gear Motor-2
Motor Driver (L298N or similar)-1
Rotating Wheel-1
Jumper Wires- as needed


📱 Mobile App

Use any standard Bluetooth terminal mobile app to send control commands like:

F — Forward

B — Backward

L — Turn Left

R — Turn Right

S — Stop

🧠 Working Principle

HC-05 receives Bluetooth signal from a mobile device.

Signal is interpreted by Arduino Uno.

Arduino sends control signals to the motor driver.

The motor driver powers the gear motors to move the wheelchair in the desired direction.

🚀 How to Run

Upload the Arduino sketch (source code) to the Uno board.

Connect the HC-05 Bluetooth module and motor driver as per the wiring diagram.

Pair the HC-05 module with your smartphone.

Open your Bluetooth controller app and send commands.

Observe the wheelchair move as per your inputs.

🤝 Contribution

Feel free to fork this repository and improve the code, structure, or functionality. Pull requests are welcome!

🙋 Author

Md.Jabir Hossen Nayan — 4th Year ICT Student, MBSTU

GitHub: JHNayan23
