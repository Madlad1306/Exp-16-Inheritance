
# Inheritance and Access Specifiers in C++

### Introduction

C++ supports **Object-Oriented Programming (OOP)** concepts, where **inheritance** and **access specifiers** are essential for creating modular, reusable, and maintainable code.

* **Access Specifiers** control visibility of class members.
* **Inheritance** allows a new class (derived/child) to reuse and extend features of an existing class (base/parent).

---

## Access Specifiers in C++

| Specifier | Inside Class | Derived Class | Outside Class |
| --------- | ------------ | ------------- | ------------- |
| Public    | Yes          | Yes           | Yes           |
| Private   | Yes          | No            | No            |
| Protected | Yes          | Yes           | No            |

* **Public:** Accessible anywhere.
* **Private:** Accessible only within the class; use getters/setters for outside access.
* **Protected:** Accessible inside the class and derived classes.

---

## Inheritance in C++

### Importance

* **Code Reusability:** Derived classes reuse base class members.
* **Hierarchy Representation:** Models real-world "is-a" relationships.
* **Extensibility:** Derived classes can add new properties or override functions.

---

### Types of Inheritance

1. **Single Inheritance**

   * One base class → One derived class.
   * Public and protected members are inherited; private members are not.
   * **Example:** `Student (base) → Exam (derived)`

2. **Multiple Inheritance**

   * One derived class inherits from two or more base classes.
   * Combines features from multiple bases; name conflicts may arise.
   * **Example:** `Manager` inherits from `Employee` and `Salary`

3. **Multilevel Inheritance**

   * Derived class inherits from another derived class, forming a chain.
   * **Example:** `Gadget → Smartphone → GamingSmartphone`

4. **Hierarchical Inheritance**

   * One base class is inherited by multiple derived classes.
   * **Example:** `Vehicle → Car, Bike, Truck, Bus`

---

## Example Algorithms

### 1️⃣ Access Specifiers

* Create a class `Vehicle` with private, protected, and public members.
* Use public functions to set private/protected data.
* Derive `Car` and display the inherited and own data.

### 2️⃣ Single Inheritance

* Base class `Student` with protected `name` and `roll`.
* Derived class `Exam` adds marks.
* Display full student info in `main()`.

### 3️⃣ Multiple Inheritance

* Base classes: `Employee (name, id)` and `Salary (salary)`.
* Derived class: `Manager` combines both.
* Display complete manager information.

### 4️⃣ Multilevel Inheritance

* Base: `Gadget (brand)` → Derived: `Smartphone (model)` → Derived: `GamingSmartphone (specs)`.
* Assign values and display all properties in `main()`.

### 5️⃣ Hierarchical Inheritance

* Base: `Vehicle (brand)` → Derived: `Car, Bike, Truck, Bus`.
* Each derived class adds unique attributes.
* Display all details using parent and child members.

---

## Conclusion

* **Access Specifiers** ensure proper encapsulation and control visibility.
* **Inheritance** allows code reuse, reduces redundancy, and builds hierarchical relationships.
* Understanding **single, multiple, multilevel, and hierarchical inheritance** creates **clean, modular, maintainable, and extensible programs**.
* These concepts form the foundation for advanced OOP principles like **polymorphism and abstraction**.



Do you want me to do that next?
