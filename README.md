# KnobLED
int ledPin = 9; int potPin = 0;  void setup() {  }  void loop() {   // read from the potentiometer   int potValue = analogRead(potPin);   // convert the reading to a value in the range we want   potValue = int(potValue/4);   // write that value to the led pin   analogWrite(ledPin, potValue); }
