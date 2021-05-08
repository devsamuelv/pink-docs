# Calulating Motor Speed And Angle

**I will add more detail later**

### Defining The Robots Constants (Inches)

- **REMEMBER: The Length And The Height is Spicific to Your Robot!!**

```java
double L = RobotContainer.Length; // 27 inch
double W = RobotContainer.Width; // 32 inch
double R = Math.sqrt(Math.pow(L, 2) + Math.pow(W, 2));
```

#### Calulating Motor Powers

```java
double A = STR - RCW * (L / R);
double B = STR + RCW * (L / R);
double C = FWD - RCW * (W / R);
double D = FWD + RCW * (W / R);
```
