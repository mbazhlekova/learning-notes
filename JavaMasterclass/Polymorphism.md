# Polymorphism

- Allows subclasses to have their own unique behavior while still sharing functionality with a parent class.

```java
class Animal {
  String talk()
}

class Cat extends Animal {
  String talk() {
    return "Meow"
  }
}

class Dog extends Animal {
  String talk() {
    return "Woof"
  }
}
```
