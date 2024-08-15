## Steps to Create, Compile, and Run a C Program on Mac Using Vim
1. Create a C Program
- Navigate to your desired directory:
   - Open Vim to create a new C file:
     ```
     vim hello.c
     ```
   - Enter insert mode by pressing `i`, and then type the following code:
     ```c
     #include <stdio.h>

     int main() {
         printf("Hello, World!\n");
         return 0;
     }
     ```
   - Save and exit Vim:
     - Press `Esc` to enter normal mode and exit insert mode.
     - Type `:wq` and hit Enter to save and exit the c file.

2. Compile the C Program
   - Compile the program using gcc:
     ```
     gcc hello.c -o hello
     ```

3. Run the C Program
   - Execute the compiled program:
     ```
     ./hello
     ```
