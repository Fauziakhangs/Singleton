# Singleton Pattern Java Program

**❗ Overview**

This project demonstrates a customized Singleton design pattern implemented in Java. The main objective is to restrict the creation of instances of the SingletonAssignment2 class to a maximum of three. If a user tries to create more than three instances, the program prevents it and displays an appropriate message, ensuring controlled instance management.


**🛠️ Tools Used**

The program is built using the Java programming language and utilizes the Java Development Kit (JDK) for compilation and execution. The Scanner class is used to handle user input via the console, allowing interactive prompts during runtime.


**🔄 Approach**

The SingletonAssignment2 class contains a private constructor to prevent direct instantiation. A static method getInstance() manages instance creation by maintaining a count and ensuring no more than three instances are created. When the limit is reached, further requests return null and notify the user. The SingletonTest class drives the program, prompting users if they want to create an instance and displaying relevant messages based on the current count of instances. This interactive approach helps demonstrate how the singleton pattern can be modified to allow a limited number of instances rather than just one.


**✅ Outcome Achieved**

The program successfully restricts the number of instances of the singleton class to three, providing clear feedback to the user. It highlights the flexibility of the Singleton pattern by implementing a controlled multi-instance limit while ensuring proper instance management and user communication throughout the execution
