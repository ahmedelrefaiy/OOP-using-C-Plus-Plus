# OOP Using C++ Course

Welcome to the **Object-Oriented Programming (OOP) using C++** course repository.  
This course covers the core concepts of OOP from the ground up — starting with why we need OOP, moving through classes, objects, memory layout, and key OOP principles.

---

## 📚 Course Content

| Week | Lecture Topics | Videos | Lecture files | Topics Covered |  Labs  |
|:----:|----------------|--------|---------------|----------------|--------|
| 1 | OOP Intro + UML Diagrams | [Video1](https://youtu.be/qmFFvOyqDHM) - [Video2](https://youtu.be/l53QxoLMgEA) - [Video3](https://youtu.be/eTgB5Zo11q0) | [Video1 PDF](Videos%20converted%20to%20pdf/1-%20C%20%20_Object-Oriented_Fundamentals.pdf) <br>[Video2 PDF](Videos%20converted%20to%20pdf/2-%20From_Spaghetti_Code_to_OOP_Entities.pdf) <br>[Video3 PDF](Videos%20converted%20to%20pdf/3-%20OOP_Modeling_and_UML_Blueprints.pdf) <br><br> [Lecture1 reference](Lectures/Lecture1_IntroductionToOOP.pdf) | ▸ Programming paradigm: Linear VS Structure VS OOP <br> ▸ Structure programming VS procedural programming <br> ▸ Structure programming problems implying to move to OOP <br> ▸ Why we need OOP? What is OOP? <br> ▸ OOP Principles <br> ▸ Convert problems to entities and classes <br> ▸ What, why, How UML? <br> ▸ Relation between OOP and UML | [Lab1](Labs/Lab1%20and%202.pdf) |
| 2 | Access Modifiers, Setter & Getter (Encapsulation VS Data Hiding) | [Video3](https://youtu.be/eTgB5Zo11q0) (last part: access modifiers) - [Video4](https://youtu.be/WHm05r26nP8) | [Video4 PDF](Videos%20converted%20to%20pdf/4-%20Encapsulation_Data_Hiding.pdf) <br><br> [Lecture2 reference](Lectures/Lecture2_Setter_Getter.pdf) | ▸ Access Modifiers <br> ▸ Class & Object syntax <br> ▸ Where to write class? <br> ▸ Setters VS Getters (Mutators VS Accessor) <br> ▸ Encapsulation VS Data Hiding <br> ▸ Getters with const | [Lab2](Labs/Lab1%20and%202.pdf) |
| 3 | Constructor | [Video5](https://youtu.be/WHm05r26nP8) | [Video5 PDF](Videos%20converted%20to%20pdf/5-%20Constructors.pdf) <br><br> [Lecture3 reference](Lectures/Lecture3_Constructor.pdf) | ▸ Constructor <br> ▸ Default and Overloaded constructor <br> ▸ Why we need Constructor? <br> ▸ Initializer List <br> ▸ Constructor with Code reusability | [Lab3](Labs/Lab3.1.pdf) - [Lab3](Labs/Lab3.2.pdf) |
| 4 | Objects & Object Members in Memory - Inline VS Regular Functions + Pointer | [Video6](https://youtu.be/UmIjxC-mVFg) - [Video7](https://youtu.be/B9iN9eubpek) | [Video6 PDF](Videos%20converted%20to%20pdf/6-%20Memory_and_inline_VS_regular.pdf) <br>[Video7 PDF](Videos%20converted%20to%20pdf/7-%20This_Pointer__Pointers_and_Memory.pdf) | ▸ Objects & its members in memory <br> ▸ Inline VS Regular function <br> ▸ Inline VS Regular function in OOP <br> ▸ This Pointer in constructor <br> ▸ Revision: What is pointer, why use arrow operator <br> ▸ Create pointer to object | [Lab4](Labs/Lab4.pdf) |
| 5 | Static VS Dynamic Memory - Pointers in depth | [Video8](https://youtu.be/rON6ZSkYWYA) - [Video9](https://youtu.be/YzlLhu0VL9I) |  | ▸ Memory Management (Memory Regions) <br> ▸ Compiler Management VS Developer Management (Static Memory VS Dynamic Memory) <br> ▸ Manage pointer in Stack or Heap or both? <br> ▸ Difference between Static Memory VS Dynamic Memory <br> ▸ Where Object and Members Stored? in Heap or Stack? <br> ▸ Pointers dangling problem <br> ▸ Array with Static Memory (Overflow Problem) <br> ▸ Pointer to stack address <br> ▸ Memory Leak Problem <br> ▸ Pointer to array with default value | [Lab5](Labs/Lab5.pdf) |
| 6 | Dynamic allocation inside classes + Static members + Copy Constructor + Constructor VS Destructor | [Video10](https://youtu.be/3HEk33SrU6U) - [Video11](https://youtu.be/Q5zvOBeOfsA) - [Video12](https://youtu.be/XCkIV35Vzjg) - [Video13](https://youtu.be/Ou7DuC_BPE8) - [Video14](https://youtu.be/h4MTxIQYrJo) |  | ▸ static VS dynamic object allocation <br> ▸ Static Array inside class <br> ▸ Why we need Static Member <br> ▸ Dynamic array inside class <br> ▸ What is Destructor? Why? <br> ▸ Delete object pointer fire destructor? + order of destructors execution <br> ▸ Constructor VS Destructor (order of execution examples) <br> ▸ Initialize object from another one <br> ▸ Copy Constructor <br> ▸ Pass and return object to/from function <br> ▸ Array of objects, const object | [Lab6](Labs/Lab6.pdf) |
| ***break*** | *Trial exam questions* | [Video15](https://youtu.be/4fUE2uSMf3Q) |  |  | [Trial exam questions](Labs/Practical%20Questions.pdf) |
| 7 | Holiday |  |  |  |
| 8 | Inheritance | [Video16](https://youtu.be/YsgVxQPxM_A) - [Video17](https://youtu.be/oqglMynuLv4) |  | ▸ what is inheritance <br> ▸ Inheritance VS Composition <br> ▸ Inheritance syntax <br> ▸ constructor & destructor order <br> ▸ inheritance class access specifications <br> ▸ Override <br> ▸ Trial Exam Questions on inheritance| [Lab7-8](Labs/Lab7-8.pdf) |
| 9 | Midterm |  |  |  |
| 10 | Virtual Functions (Static VS Dynamic Binding) + Polymorphism + Abstraction | [Video18](https://youtu.be/APOSbeDyHLw) - [Video19](https://youtu.be/Md-FL2rWbAA) |  | ▸ Static VS Dynamic Binding <br> ▸ Redefine VS Override function <br> ▸ Pointer to object with inheritance <br> ▸ why we need virtual in destructor <br> ▸ Polymorphism <br> ▸ overloading VS Overriding ▸ multiple inheritance ambiguous problems <br> ▸ inheritnace types (single, multiple, multilevel, hierarchical) <br> ▸ Polymorphism powerful with array of parent point to many children example <br> ▸ Abstraction - (interface) <br> ▸ why we need Abstraction? (real world examples) <br> ▸ From inheritance example to the power of Abstraction <br> ▸ Trial Exam questions <br> | [Lab7-8](Labs/Lab7-8.pdf) |
| 11 **(Current)** | Templates + Operators overloading |  [Video20](https://youtu.be/f_JQ5vaphQg) - [Video21](https://youtu.be/R-0Mj81xxGI) - [Video22 (https://youtu.be/uRcaVP8lo9M)  |  | ▸ All Types of Polymorphism <br> ▸ Template Functions, relation with overloading <br> ▸ Template Function with single or multiple types <br> ▸ typename vs class keyword <br> ▸ Template Class <br> ▸ when we need templates <br> ▸ behaviour of compiler with templates <br> ▸ Trial Exam practical questions on templates <br> ▸ Function overloading <br> ▸ Function overloading (member vs non-member functions) <br> ▸ when and why we need Function overloading <br> ▸ friend function, when to use it <br> ▸ summary to all polymorphism types <br> ▸ Copy Constructor VS Assignment Operator interview Cases <br> ▸ Practical real life examples <br> | |
| 12 | Exception, File I/O |  |  |  |
| 13 | OOD: SOLID Principles + Design Patterns (simple ones) |  |  |  |

---

## 🎥 YouTube Playlist

All lecture videos are available on YouTube. Links are provided in the table above for each week.

---

## 👨‍🏫 Instructor

**Ahmed Elrefaiy**

---

> ⭐ If you find this course helpful, please give this repo a star!
