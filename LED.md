三個LED燈循環亮

![圖片](https://user-images.githubusercontent.com/16370565/131235821-70844b3e-beb3-4716-9004-a612e2288ff8.png)

void setup() <br>
{ <br>
  pinMode(13,OUTPUT); <br>
} <br>
 <br>
void loop()  <br>
{ <br>
  digitalWrite(13,HIGH); <br>
  delay(500); <br>
  digitalWrite(13,LOW); <br>
  delay(500); <br>
  digitalWrite(11,HIGH); <br>
  delay(500); <br>
  digitalWrite(11,LOW); <br>
  delay(500); <br>
  digitalWrite(9,HIGH); <br>
  delay(500); <br>
  digitalWrite(9,LOW); <br>
  delay(500); <br>
} <br>
