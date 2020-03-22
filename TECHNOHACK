#define trigPin1 A0
#define echoPin1 A1

#define trigPin2 A2
#define echoPin2 A3

#define trigPin3 A4
#define echoPin3 A5


#define motor1 5
#define motor2 6
#define buzzer 3

void setup()
{
pinMode(trigPin1, OUTPUT);

pinMode(echoPin1, INPUT);

pinMode(trigPin2, OUTPUT);

pinMode(echoPin2, INPUT);

pinMode(trigPin3, OUTPUT);

pinMode(echoPin3, INPUT);


pinMode(motor1, OUTPUT);

pinMode(motor2, OUTPUT);

pinMode(buzzer,OUTPUT);

}

void loop()

{

long duration, distance;

digitalWrite(trigPin1, LOW); 

delayMicroseconds(2); 

digitalWrite(trigPin1, HIGH);

delayMicroseconds(1); 

digitalWrite(trigPin1, LOW);

duration = pulseIn(echoPin1, HIGH);

distance = (duration/2) / 29.1;

if (distance < 45)

{ 

 

digitalWrite(buzzer,HIGH);

} else

{



digitalWrite(buzzer,LOW); 

} delay(50);



digitalWrite(trigPin2, LOW); 

delayMicroseconds(2); 

digitalWrite(trigPin2, HIGH);

delayMicroseconds(1); 

digitalWrite(trigPin2, LOW);

duration = pulseIn(echoPin2, HIGH);

distance = (duration/2) / 29.1;

if (distance < 40)

{ 

digitalWrite(motor1,HIGH);



} else

{

digitalWrite(motor1,LOW);

 

} delay(100);




digitalWrite(trigPin3, LOW); 

delayMicroseconds(2); 

digitalWrite(trigPin3, HIGH);

delayMicroseconds(2); 

digitalWrite(trigPin3, LOW);

duration = pulseIn(echoPin3, HIGH);

distance = (duration/2) / 29.1;

if (distance < 30)

{ 

digitalWrite(motor2,HIGH); 

} else

{

digitalWrite(motor2,LOW);

 

} delay(100);

}
