# polymorphism-in-java
public class Main
{
  public static void main(String args[])
  {
    Animal A1 = new Dog();
    Animal D1= new Cat();
    A1.makeSound();
    D1.makeSound();
  }
}
