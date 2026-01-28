# Automatic-traffic-lights
I made an automatic traffic light



void setup() {



pinMode(2, OUTPUT);
pinMode(3, OUTPUT);
pinMode(4, OUTPUT);
pinMode(5, OUTPUT);
}

void loop() {




digitalWrite(2, HIGH);
delay(1500);
digitalWrite(2, LOW);
delay(100);
digitalWrite(4, HIGH);
delay(2500);
digitalWrite(4, LOW);
delay(100);
digitalWrite(3, HIGH);
delay(1500);
digitalWrite(3, LOW);
delay(100);
}
