# MyFirstProject1
#define segA 2
#define segB 3
#define segC 4
#define segD 5
#define segE 6
#define segF 7
#define segG 8

void setup() 
{  
pinMode(segA,OUTPUT);
pinMode(segB,OUTPUT);
pinMode(segC,OUTPUT);
pinMode(segD,OUTPUT);
pinMode(segE,OUTPUT);
pinMode(segF,OUTPUT);
pinMode(segG,OUTPUT);
}

void loop() {
 digitalWrite(segA,HIGH);// DIGIT 0
 digitalWrite(segB,HIGH);
 digitalWrite(segC,HIGH);
 digitalWrite(segD,HIGH);
 digitalWrite(segE,HIGH);
 digitalWrite(segF,HIGH);
 digitalWrite(segG,LOW);
 delay(1000);
 
 digitalWrite(segA,LOW);// DIGIT 1
 digitalWrite(segB,HIGH);
 digitalWrite(segC,HIGH);
 digitalWrite(segD,LOW);
 digitalWrite(segE,LOW);
 digitalWrite(segF,LOW);
 digitalWrite(segG,LOW);
 delay(1000);
  digitalWrite(segA,HIGH);// DIGIT 2
 digitalWrite(segB,HIGH);
 digitalWrite(segC,LOW);
 digitalWrite(segD,HIGH);
 digitalWrite(segE,HIGH);
 digitalWrite(segF,LOW);
 digitalWrite(segG,HIGH);
 delay(1000);
 
 digitalWrite(segA,HIGH);// DIGIT 3
 digitalWrite(segB,HIGH);
 digitalWrite(segC,HIGH);
 digitalWrite(segD,HIGH);
 digitalWrite(segE,LOW);
 digitalWrite(segF,LOW);
 digitalWrite(segG,HIGH);
 delay(1000);
 
 digitalWrite(segA,LOW);// DIGIT 4
 digitalWrite(segB,HIGH);
 digitalWrite(segC,HIGH);
 digitalWrite(segD,LOW);
 digitalWrite(segE,LOW);
 digitalWrite(segF,HIGH);
 digitalWrite(segG,HIGH);
 delay(1000);

 digitalWrite(segA,HIGH);// DIGIT 5
 digitalWrite(segB,LOW);
 digitalWrite(segC,HIGH);
 digitalWrite(segD,HIGH);
 digitalWrite(segE,LOW);
 digitalWrite(segF,HIGH);
 digitalWrite(segG,HIGH);
 delay(1000);

 digitalWrite(segA,HIGH);// DIGIT 6
 digitalWrite(segB,LOW);
 digitalWrite(segC,HIGH);
 digitalWrite(segD,HIGH);
 digitalWrite(segE,HIGH);
 digitalWrite(segF,HIGH);
 digitalWrite(segG,HIGH);
 delay(1000);

 digitalWrite(segA,HIGH);// DIGIT 7
 digitalWrite(segB,HIGH);
 digitalWrite(segC,HIGH);
 digitalWrite(segD,LOW);
 digitalWrite(segE,LOW);
 digitalWrite(segF,LOW);
 digitalWrite(segG,LOW);
 delay(1000);

 digitalWrite(segA,HIGH);// DIGIT 8
 digitalWrite(segB,HIGH);
 digitalWrite(segC,HIGH);
 digitalWrite(segD,HIGH);
 digitalWrite(segE,HIGH);
 digitalWrite(segF,HIGH);
 digitalWrite(segG,HIGH);
 delay(1000);

 digitalWrite(segA,HIGH);// DIGIT 9
 digitalWrite(segB,HIGH);
 digitalWrite(segC,HIGH);
 digitalWrite(segD,LOW);
 digitalWrite(segE,LOW);
 digitalWrite(segF,HIGH);
 digitalWrite(segG,HIGH);
 delay(1000);

}
