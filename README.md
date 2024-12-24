# Relay_Control_via_touch

This project showcases a touch-sensitive relay control system using the ESP32 microcontroller. The system employs the ESP32's built-in capacitive touch sensor on pin T7 (GPIO 27) to toggle a relay connected to GPIO pin 13. A touch threshold is set to 40, and an interrupt service routine (ISR) detects touch events, switching the relay on or off accordingly. The system provides real-time feedback via the serial monitor, demonstrating the ESP32's touch sensing capabilities for practical applications in home automation and touch-based device control.
Make the necessary connections and upload the code onto the ESP32 board.
Touch the wire connected to D27 to see the relay switch to NO and NC thus, making the LED toggle.





