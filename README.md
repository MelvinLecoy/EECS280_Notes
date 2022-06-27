# EECS 280 Notes

<details>
<summary>Chp 1: Machine Model and Procedural Abstraction</summary>

-   <details>
    <summary>Diagram of software program stages</summary>

    <img src="https://s3.us-west-2.amazonaws.com/secure.notion-static.com/40ad7c1d-1cb5-4764-a0a3-327b78819695/Untitled.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Content-Sha256=UNSIGNED-PAYLOAD&X-Amz-Credential=AKIAT73L2G45EIPT3X45%2F20220627%2Fus-west-2%2Fs3%2Faws4_request&X-Amz-Date=20220627T141943Z&X-Amz-Expires=86400&X-Amz-Signature=3bee3aeb7afdad778e46058cb805b62346651a11fdce9be4e63af576dbdfbc63&X-Amz-SignedHeaders=host&response-content-disposition=filename%20%3D%22Untitled.png%22&x-id=GetObject" width="500" height="200">
    </details>

-   <details>
    <summary>Terminology</summary>

    -   <details>
        <summary>Variable vs Objects</summary>

        Variable | Object
        --- | ---
        Name that refers to object in memory | Data that’s located in some address in memory
        Created at Compile time (source code) | Created at Runtime

        - Many variable names for 1 object: **Reference variables**
        - 1 variable name for many objects: **Arrays**
        - No variable name for 1 object: **Dynamic Memory**
        </details>

    -   <details>
        <summary>Compile time vs Runtime</summary>

        - Compile time
            > Compile time is the period when source code is converted to machine code or binary code. The compiler check for the syntax and semantics of the code.
            > 
            > Source code, dependent files, interfaces and required libraries are inputs and a complied assembly code returns as outputs, otherwise compile time error
            > 
            > Assembly code is after compile time (at runtime)
        - Runtime
            > A program’s lifetime is a runtime when the program is in execution
            > 
            > Examples of Runtime error: 
            > - **Division by zero (error based on value)**
            > - **Dereferencing a null pointer (attempts to access memory with a NULL)**
            > - **Running out of memory (stack overflow)**
        - Difference
            Compile time | Runtime
            --- | ---
            Period to translate source code to intermediate code like .exe | Period between start of running intermediate code through Assembly code and finish running at a runtime environment
            Check syntax and semantics; error get detected by compiler without execution of program | Run the code and only detected after execution of program
            When we just look at the source code, variables don’t have value | Objects have values when we run the program (Value is only meaningful during execution)
        </details>

    -   <details>
        <summary>Lifetime: the storage duration of an object</summary>

        - **Static**: for the whole program
        - **Automatic**/**Local**: lifetime is tied to a scope during execution of its local block
        - **Dynamic**: the object is explicitly created and destroyed by the user
        </details>

    </details>

-   <details>
    <summary>Procedural Abstraction (Separate files)</summary>

    * Never include a `.cpp` source file in header file and never put `.h` file in compiler terminal command
    * Never include `using namespace std;` inside a header file
    </details>

</details>

<details>
<summary>Chp 2</summary>

</details>
