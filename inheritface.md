### Given the code below. What is the most probable outcome?
![code sample](https://nachowolf.github.io/OCA-Prep-Questions/resources/images/interheritance.png)

```
package Quests;

interface Animal {
    void walk();
    void run();
    void jump();
    void sleep();
}
    public class Cat extends Animal{
        public void walk(){}
        public void run(){}
        public void jump(){}
        public void sleep(){}

        public static void main(String[] args) {
            Animal Cat = new Cat();
        }
    }
```

