int buttonState1=0;
int buttonState2=0;

const int buttonPin1=10;
const int buttonPin2=11;

void setup() {
pinMode(LED_BUILTIN,OUTPUT);
pinMode(buttonPin1,INPUT_PULLUP);
pinMode(buttonPin2,INPUT_PULLUP);
}


void loop() {
buttonState1 = digitalRead(buttonPin1);
buttonState2 = digitalRead(buttonPin2);

if(buttonState1 == HIGH && buttonState2 == HIGH){
digitalWrite(LED_BUILTIN,LOW);
}

else if(buttonState1 == LOW || buttonState2 == HIGH){
  digitalWrite(LED_BUILTIN,HIGH);
}

else if(buttonState1 == HIGH || buttonState2 == LOW){
  digitalWrite(LED_BUILTIN,HIGH);
}

else{
digitalWrite(LED_BUILTIN,LOW);
}

}
