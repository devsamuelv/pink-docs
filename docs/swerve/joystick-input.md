# Getting Input From The Joystick

#### Getting The Joystick Input

- **FWD** is forward or y axis
- **STR** is sideways or x axis
- **RCW** is rotation or z axis

```java
double x = m_baseJS.getRawAxis(0);
double y = m_baseJS.getRawAxis(1);
double z = m_baseJS.getRawAxis(4);

double FWD = y;
double STR = x;
double RCW = z;

double temp = FWD * Math.cos(0) + STR * Math.sin(0);
STR = -FWD * Math.sin(0) + STR * Math.cos(0);
FWD = temp;
```
