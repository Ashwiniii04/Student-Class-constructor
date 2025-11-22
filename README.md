## Student Class - C++ OOP Demonstration
A C++ program demonstrating Object-Oriented Programming concepts using a Student class.
📚 Concepts Demonstrated

Classes and Objects - Creating a Student class with multiple attributes
Constructors - Multiple types of constructors:

Default Constructor
Parameterized Constructor (multiple variations)
Copy Constructor (implicit)


Member Functions - Display function to print student information
Object Creation - Different ways to create and initialize objects

🎯 What This Program Does
Creates multiple student objects using different constructor types and displays their information.
💻 How to Compile and Run
bash# Compile the program
g++ student_class.cpp -o student

# Run the program
./student
📤 Example Output
--- Student Information ---

Name: ALEX | Section: B | Roll No: 5 | Marks: 9.8
Name: LUNA | Section: A | Roll No: 26 | Marks: 8.5
Name: RACHEL | Section: C | Roll No: 20 | Marks: 6.7
Name: ROSS | Section: A | Roll No: 27 | Marks: 8.5
🔍 Code Explanation
Constructor Types Used:

Default Constructor

cpp   Student s2;  // Creates object with default values

Parameterized Constructor

cpp   Student s1("ALEX", 'B', 5, 9.8);  // Direct initialization

Constructor with Different Parameter Order

cpp   Student s3(20, 'C', 6.7, "RACHEL");  // Shows constructor overloading

Copy Constructor

cpp   Student s4 = s2;  // Creates a copy of s2
✨ Key Learning Points

How to define a class in C++
Creating multiple constructors (constructor overloading)
Difference between default and parameterized constructors
How copy constructor works (deep copy vs shallow copy)
Using member functions to access object data

🛠️ Technologies Used

Language: C++
Compiler: g++ (GCC)

📖 Related Topics

Object-Oriented Programming
Encapsulation
Constructor Overloading
Member Functions


Part of my C++ learning journey 📚 | MSc Bioinformatics Student
