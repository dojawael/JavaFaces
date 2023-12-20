# A short story about emotion faces

## The idea of the project is:

First of all, if you run your project you will see a smiling face 😀, then if you touch it you will see a VERY nervous face 🙄, because it's very sensitive, and will at the end it will be dizzy 😵, lastly 🥴 will fall down.

I know that is kindda imaginary story you have ever seen, but it's very helpful and has many benefits that will help you understand the basic concepts of Java Programming.


## key goals to follow up with my project:

✅ learn the basics of Java:
- How to create variables?
- How to create frames with Java?
    - How to add images.
- How to add an event listener (mouse listener)?
- How to write statements (if/else, loops)?

> Regardless of how basic the project is, it is easy to follow up and absorb the core Java concepts.

> Remember, learning programming can't be without building projects!

---


### Finally, let's dive into the project.

**How to start a java Project?**

- 📌 First will create a file called ```Main.java``` and contain our classes in it. 
- 📌 Second, with our second file we declare 3 imports:
```Java 
//MyFrame.java
import java.awt.FlowLayout;
import java.awt.event.*;
import javax.swing.*;
```
- 📌 Third we create a frame and include the size and the layout.
```Java
// MyFrame.java

 MyFrame() {
    this.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
    this.setSize(500,500);
    this.setLayout(new FlowLayout());

    .....
}
```
- 📌 Foruth we add our pictures to the frame .
```Java
// create a variable to hold pics sources
// add your pics source if your pic inside a folder add the name without . or / e.g.

pain = new ImageIcon("images/pain.png");
```
- 📌 Finally we include 5 methods to handle mouseListener and show different emetions.
```Java
@Override

// TODO: add the rest of the emotions according to this method.
public void mousePressed(MouseEvent e) {
    label.setIcon(pain);
}
```
> ```@Override``` is declaring a method in sub class, which is already present in parent class.
done so that a child class can give it's own implementation. [Read More...](https://www.programiz.com/java-programming/method-overriding)


---

### 💟 THANK YOU FOR SEEING MY PROJECT 💟 
**Don't Forget to give me a ⭐️ at the top of this repo you will find it! and share it with others.**v