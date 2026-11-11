# Mission 4 —Understanding How Programs Run

## Task
To run a basic Python script and compare how compilers and interpreters handle code translation.



### Task 4.1 — Python Execution Result
Wheb I ran the `hello.py` program successfully in the terminal, and it outputted the text: `Hello from Python`.

---

### Task 4.2 — Compiler vs Interpreter Comparison Table

| Point | Compiler | Interpreter |
| :--- | :--- | :--- |
| **When it translates** |It Translates the whole (whole machine code) program all at once before running it. |whereas,Interpreters Translate and run the code line-by-line while it runs. |
| **Typical output** | Generates an executable file (.exe file). |there is no separate output file, it executes the code directly. |
| **One example** | C++ or Java | Python or JavaScript |
| **One advantage** | The program runs much faster once it is compiled. | It is easier to test and find bugs while writing code. |

### Summary Explanation
* A compiler changes the entire source code file into machine language before any execution starts, which makes the final program run very fast. 
* On the other hand, an interpreter reads and runs the code step-by-step at runtime, meaning it translates as it goes. Because of this, 
* compiled languages are great for speed, while interpreted languages like Python are much easier for testing and fixing mistakes quickly.

## 3. Commands / tools used
* `python3 hello.py` - Run my Python file in the terminal.

## 4. My understanding
I learned that computers can't read code directly until it is translated. Compilers do all the translation work upfront to make a fast standalone file, while interpreters translate instructions on the fly line-by-line while the program runs.


**Difficulties faced**
learing about compilers and interpreters was a bit challenging,other than that it was easy.

##  Evidence / files
* `hello.py`
* `mission-04-programs/README.md`

##  Commit details
* **Commit Message:** "Compare compilers and interpreters"
