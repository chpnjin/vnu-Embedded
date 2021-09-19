![2021-09-05 10_43_28-Circuit design 3色LED+示波器 _ Tinkercad — Mozilla Firefox](https://user-images.githubusercontent.com/16370565/132113156-523dc903-ac39-44b4-a36d-73b88c4274fd.png)

````C
const int R = 9 ;
const int G = 10 ;
const int B = 11 ;

  void setup()
{
  pinMode(R, OUTPUT);
  pinMode(G, OUTPUT);
  pinMode(B, OUTPUT);
}

void loop()
{
  analogWrite(R,255);
  analogWrite(G,0);
  analogWrite(B,0);

    delay(1000);
  analogWrite(R,0);
  analogWrite(G,255);
  analogWrite(G,255);

    delay(1000); 
  analogWrite(R,0);
  analogWrite(G,0);
  analogWrite(B,255);

   delay(1000); 
}
````
