# Using Variables, Declaring Constants

* variables are tools that temporarily store data for a finite duration
* constants are tools that define unalterable artifacts

## What is a Variable?

### Memory and Addressing in Brief

* memory for temporary storage is called Random Access Memory (RAM)
* In order to access a location in memory (real example here), the processor needs to be asked (via an instruction) to fetch a value from the address or write a value to the address.

### Declaring Variables to Access and Use Memory

* Pattern to define a variable: `variable_type variable_name;` or `variable_type variable_name = initial_value;` 
* The variable type attribute tells the compiler the nature of data the variable can store, and the compiler reserves the necessary space for it.
* **Initialization is good programming practice.** 
* In contrast to assembly language (in which the programmer needs to explicitly ask the processor to store a value in a specific address), C++ enables the programmer the access memory locations to store and retrieve data using friendlier concepts such as variable assignment. The compiler does the job of mapping a variable to a location in memory and associated bookkeeping.

### Declaring and Initializing Multiple Variables of a Type

* The programmer could condense declaration of variables to one line: `int FirstNumber = 0, SecondNumber = 0, MultiplicationResult = 0;`

### Understanding the Scope of a Variable

*  

### Global Variable

* Using global variables indiscriminately is generally considered poor programming practice

# Common Compiler-Supported C++ Variable Types

| Type | Values |
| ---- | -----: |
| `bool` | `true` or `false` |
| `char` | 256-character values |

* Compiling and running an application: `g++ my_app.cpp -o my_app.exe; ./my_app.exe`
