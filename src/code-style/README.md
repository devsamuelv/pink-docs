---
sidebar: auto
---

# Code Style

## Functions

### Naming

For Function nameing start with a lower case character then for other words make the first character capitalized

#### Example

```java
public void myFunc() {}
```

### Arguments

For Args In a function make sure they have a underscore in front of them to differentiate the global varibles from the local ones

#### Example

```java
public void myFunc(String _name) {
  system.out.Println(_name);
}
```

<!-- ----------------------------------------------------------------------- -->
<!--                            end of functions                             -->
<!-- ----------------------------------------------------------------------- -->

## Varibles

<!-- ### Global Varibles -->

```java
// Constants will start with a captial
public final String Message = "hello";

// Non-Constants will start with a lower case character
public String messagePayload = "hello, nice to meet you";
```

<!-- ----------------------------------------------------------------------- -->
<!--                             end of varibles                             -->
<!-- ----------------------------------------------------------------------- -->

## Classes

- Classes Should Have Every Word Including The Starting Charicter To be Capital

### Naming

- **Example**

```java
class ExampleClass {}
```

### Wrapper's

When Making a Wrapper, Extending the class your making this wrapper for example `extends TalonFX` is prefered as it makes it easier for creating a wrapper mainly because you don't need to redefine all the functions and if you want to change one all you need to use is a `@Override` statement above a function

- **Example**

```java
class ExampleClass extends TalonFX {
  public ExampleClass() {
    super();
  }

  @Override
  void Send() {
    this.set(ControlMode.Percent, 1);
  }
}
```
