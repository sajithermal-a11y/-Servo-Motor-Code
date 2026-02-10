# -Servo-Motor-Code
#include <Servo.h>

Servo myServo;

void setup() {
  myServo.attach(9);   // Servo signal pin
}

void loop() {
  myServo.write(0);    // Move to 0 degree
  delay(1000);

  myServo.write(90);   // Move to 90 degree
  delay(1000);
}
