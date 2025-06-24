# SuT_optionalTask
Optional Task – Week 1 (Summer Training)

## About This Task
A simple exercise involving sequential lighting of two LEDs using Arduino.

## Hardware Configuration
 - using a simulator:
 ![Screenshot (510)](https://github.com/user-attachments/assets/682456f0-2595-47cc-8997-1d7b3e1dd516)







- using hardware:
![SuT_optionalT_HW](https://github.com/user-attachments/assets/9e6d5b10-be29-46dd-9901-cdfcda46552a)


Note: A 470-ohm resistor was used in this setup as an optional component, it was included as a precaution to limit current. 



## Implementation

```
// C++ code
//
void setup()
{
  pinMode(13, OUTPUT);
}

void loop()
{
  digitalWrite(13, HIGH);//5 volt
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(12, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(11, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
  
  digitalWrite(13, LOW);//5 volt
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(12, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(11, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
  
  
  digitalWrite(13, LOW);//5 volt
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(12, LOW);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(11, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  
  
}
```


