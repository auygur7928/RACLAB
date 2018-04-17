#include<Servo.h>

Servo servo1 , servo2, servo3;

  
int pot1,pot2,pot3;


void setup() {
 servo1.attach(9);
 servo2.attach(10);
 servo3.attach(11);
Serial.begin(9600);

}

void loop() {

pot1=analogRead(A0);
pot2=analogRead(A1);
pot3=analogRead(A2);


pot1=map(pot1,0,1023,1,179);
pot2=map(pot2,0,1023,1,179);
pot3=map(pot3,0,1023,1,179);


servo1.write(pot1);
servo2.write(pot2);
servo3.write(pot3);
delay(150);
}
