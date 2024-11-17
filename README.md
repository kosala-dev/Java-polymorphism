# Java Method Overloading and Overriding Example  

This repository showcases examples of **method overloading** and **method overriding** in Java using the `parent_overriding` and `child_overriding` classes.  

---

## 📂 Project Contents  

### 1. **parent_overriding.java**  
   - **Description**:  
     - Contains the `phone()` method, which outputs "samsung" to the console.  
     - Serves as the parent class to demonstrate method overriding.  

### 2. **child_overriding.java**  
   - **Description**:  
     - Extends the `parent_overriding` class and overrides the `phone()` method to output "Nokia".  
     - Includes an overloaded version of the `phone()` method with a parameter to demonstrate method overloading.  

---

## ✨ Features  

1. **Method Overriding**:  
   - Allows the child class to provide its own implementation of a method defined in the parent class.  
   - Example:  
     - In `parent_overriding`, `phone()` outputs "samsung".  
     - In `child_overriding`, `phone()` is overridden to output "Nokia".  

2. **Method Overloading**:  
   - Enables multiple methods with the same name but different parameter lists.  
   - Example:  
     - `phone()` outputs "Nokia".  
     - `phone(String x)` outputs "Redmi".  

---

## 🚀 How to Run  

1. Clone the repository:- 
   ```bash
   git clone https://github.com/kosala-dev/java-method-overloading-overriding.git
2. Compile the codes:- 
   javac parent_overriding.java child_overriding.java
   
3. Run the child_overriding class:- 
java child_overriding

🧑‍💻 Concepts Demonstrated
Overriding: Customizing a parent class method in the child class.
Overloading: Defining multiple methods with the same name but different parameter lists.

📧 Contact
For any questions or suggestions, feel free to reach out:

Email: kosalamadushan11976@gmail.com
GitHub: kosala-dev
