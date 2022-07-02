Hello World

Objectives:

Write your first java program

Let's write our very first Java program. In this lesson, we will create a HelloWorld application and go over the life cycle of a Java program.

Open up your terminal and create a new folder called javaFun. Inside of that folder, create a file named HelloWorld.java. Copy and paste the code below. Our HelloWorld.java file is called the source file and the content inside is called the source code. javaFun/HelloWorld.java
public class HelloWorld {
    public static void main(String[] args) {
        System.out.println("Hello World");
    }
}copy
In your terminal, navigate to the javaFun directory and compile our HelloWorld.java file.If you don't see any errors, that means the javac compiler successfully compiled your Java code!
javac HelloWorld.java
copy
Upon success, the Java compiler automatically generates a .class file. This file contains bytecode.

listJavaC

Bytecode is computer-independent but partially compiled. You can try opening it in your text editor and you will see that it's composed of code we did not write. The Java compiler automatically translates your source code and converts it into what you see in your .class file.

We finally have some code that our machine can understand. In your terminal, run the following:
java HelloWorld
copy
Congratulations! You just created your first Java Program!