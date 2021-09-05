三個LED燈循環亮

![圖片](https://user-images.githubusercontent.com/16370565/131235821-70844b3e-beb3-4716-9004-a612e2288ff8.png)

````C
void setup()
{
  pinMode(13,OUTPUT);
}

void loop()
{
  digitalWrite(13,HIGH);
  delay(500);
  digitalWrite(13,LOW);
  delay(500);
  digitalWrite(11,HIGH);
  delay(500);
  digitalWrite(11,LOW);
  delay(500);
  digitalWrite(9,HIGH);
  delay(500);
  digitalWrite(9,LOW);
  delay(500);
}
````
