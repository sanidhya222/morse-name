void setup() 
{
  pinMode(LED_BUILTIN,OUTPUT);                
}

void line()
{
  digitalWrite(LED_BUILTIN,HIGH);
  delay(700);
  digitalWrite(LED_BUILTIN,LOW);
  delay(1000);
}

void dot()
{
  digitalWrite(LED_BUILTIN,HIGH);
  delay(150);
  digitalWrite(LED_BUILTIN,LOW);
  delay(1000);
}

//NAME = SANIDHYA
 
void loop() 
{ 
 // S
  dot();
  dot();
  dot();
  delay(2000);

 // A
  dot();
  line();
  delay(2000);

 // N
  line();
  dot();
  delay(2000);
  
 // I
  dot();
  dot();
  delay(2000);
  
 // D
  line();
  dot();
  dot();
  delay(2000);
  
 // H
  dot();
  dot();
  dot();
  dot();
  delay(2000);
  
 // Y
  line();
  dot();
  line();
  line();
  delay(2000);                            

  // A
  dot();
  line();
  delay(2000);
  
}
