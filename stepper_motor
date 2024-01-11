
const int IN1 = 8;
const int IN2 = 9;
const int IN3 = 10;
const int IN4 = 11;

int wait_time=3;
int wait2_time=450;
int n = 0;

void setup() {
  pinMode(IN1, OUTPUT);
  pinMode(IN2, OUTPUT);
  pinMode(IN3, OUTPUT);
  pinMode(IN4, OUTPUT);
}

void loop() {
  while(n<50){
    digitalWrite(IN1,HIGH);
    digitalWrite(IN2,LOW);
    digitalWrite(IN3,LOW);  
    digitalWrite(IN4,LOW);
    delay(wait_time);

    digitalWrite(IN1,LOW);
    digitalWrite(IN2,LOW);
  
    digitalWrite(IN3,HIGH);  
    digitalWrite(IN4,LOW);  
    delay(wait_time);
 
    digitalWrite(IN1,LOW);
    digitalWrite(IN2,HIGH);
    digitalWrite(IN3,LOW);  
    digitalWrite(IN4,LOW);
    delay(wait_time);
   
    digitalWrite(IN1,LOW);
    digitalWrite(IN2,LOW);
    digitalWrite(IN3,LOW);  
    digitalWrite(IN4,HIGH);
    delay(wait_time);     
   
    n++;
    }
  n=0;
  delay(wait2_time);

  while(n<50){
    digitalWrite(IN1,LOW);
    digitalWrite(IN2,LOW);
    digitalWrite(IN3,LOW);  
    digitalWrite(IN4,HIGH);
    delay(wait_time);

    digitalWrite(IN1,LOW);
    digitalWrite(IN2,HIGH);
    digitalWrite(IN3,LOW);  
    digitalWrite(IN4,LOW);
    delay(wait_time);

    digitalWrite(IN1,LOW);
    digitalWrite(IN2,LOW);
    digitalWrite(IN3,HIGH);  
    digitalWrite(IN4,LOW);
    delay(wait_time);

    digitalWrite(IN1,HIGH);
    digitalWrite(IN2,LOW);
    digitalWrite(IN3,LOW);  
    digitalWrite(IN4,LOW);
    delay(wait_time);

    n++;
  }     
  n=0;
  delay(wait2_time);
}
