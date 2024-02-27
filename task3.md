**By Referring to C-based Lab videos and RISC-V-based lab videos**

**Snapshots of the compiled C code and RISC-V**

**Step 1: check whether the leafpad is installed in ur machine by using the commands
leafpad sum1ton.c& (sum1ton.c is the file name)
If the leafpad editor is opened without any errors then type the C code.**
****If the leafpad is not installed in ur machine then install by using the following command**

**sudo snap install leafpad****

****Step 2: Writing the C code in the leafpad editor** using the following command

**leafpad sum1ton.c&**
![Screenshot from 2024-02-27 10-28-47](https://github.com/Animeshhhh15/VSDSQUADRON-MINI-/assets/160756499/ad8d1bbf-2a29-4350-9c2f-6a2448fec160)


**Step 3: After writing the C code save the editor by Ctrl+s**

**Step 4: Check for the errors by using the following command(compilation step)**

**gcc sum1ton.c**

![Screenshot from 2024-02-27 10-00-11](https://github.com/Animeshhhh15/VSDSQUADRON-MINI-/assets/160756499/4c6c3834-6808-4baa-bf1d-1c05e79f35e1)

**Step 5: Check the output by using the command**

**./a.out**
![Screenshot from 2024-02-27 10-01-34](https://github.com/Animeshhhh15/VSDSQUADRON-MINI-/assets/160756499/28fc4fb1-c7b1-4e06-b42b-a3a4b44937af)

**The results will be displayed as** 

**Sum of numbers from 1 to 500 is 125250**


********************************************************RISCV Compilation and Execution*****************************************************

**Step 1: View the C Code in the editor window using the following command**

**cat sum1ton.c**
![Screenshot from 2024-02-27 10-04-14](https://github.com/Animeshhhh15/VSDSQUADRON-MINI-/assets/160756499/a5291396-3bd9-458a-8177-facf2e192f72)


**Step 2: Compile the code in riscv using the following command**

**riscv64-unknown-elf-gcc -O1 -mabi=lp64 -march=rv64i -o sum1ton.o sum1ton.c**
![Screenshot from 2024-02-27 10-05-02](https://github.com/Animeshhhh15/VSDSQUADRON-MINI-/assets/160756499/d5d87282-2b82-4872-8061-fd889270472e)


**Step 3: The ls ltr command in Linux is used to list the contents of the current directory in long format, sorted by last modified time in reverse order.**

**use the command**

**ls -ltr sum1ton.c**

![Screenshot from 2024-02-27 10-05-02](https://github.com/Animeshhhh15/VSDSQUADRON-MINI-/assets/160756499/8d8cf19c-e7b7-4f68-a78a-aad0d1cf4063)



![WhatsApp Image 2024-02-27 at 10 49 49 AM](https://github.com/Animeshhhh15/VSDSQUADRON-MINI-/assets/160756499/c93fab27-b779-47b4-ad0a-1f66290eb7b6)


**Search for the Main and check the instructions of the C code execution. It has 15 instructions in the C execution**

![WhatsApp Image 2024-02-27 at 10 49 50 AM](https://github.com/Animeshhhh15/VSDSQUADRON-MINI-/assets/160756499/51dcbe3b-a355-4972-8bc9-6b6e987ab84b)

![WhatsApp Image 2024-02-27 at 10 49 50 AM (1)](https://github.com/Animeshhhh15/VSDSQUADRON-MINI-/assets/160756499/83112005-ab15-45cd-b7a2-ece08707f93d)


**Step 4:**

**riscv64-unknown-elf-gcc -Ofast -mabi=lp64 -march=rv64i -o sum1ton.o sum1ton.c**

![WhatsApp Image 2024-02-27 at 10 49 51 AM](https://github.com/Animeshhhh15/VSDSQUADRON-MINI-/assets/160756499/776fc255-063b-4cde-b44a-f8397cb639e3)


![WhatsApp Image 2024-02-27 at 10 49 49 AM (2)](https://github.com/Animeshhhh15/VSDSQUADRON-MINI-/assets/160756499/4d77a9bb-96d9-43d7-ad71-bcbb37e9f2ad)


