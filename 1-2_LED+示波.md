
![2021-09-05 10_21_06-Circuit design LED波長顯示 _ Tinkercad — Mozilla Firefox](https://user-images.githubusercontent.com/16370565/132112930-7d4ac3ae-0767-4f17-9dae-b8b97f4bd484.png)

````C
int brightness = 0;

void setup()
{
  pinMode(9, OUTPUT);
}

void loop()
{
  for(brightness = 0 ;brightness <= 255;brightness += 5){
    analogWrite(9,brightness);
    delay(30);
  }
    for(brightness = 255 ;brightness <= 0;brightness -= 5){
    analogWrite(9,brightness);
    delay(30);
  }
}
````
