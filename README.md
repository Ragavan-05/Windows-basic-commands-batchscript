# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations
Create a directory named "my-folder"

## COMMAND AND OUTPUT

<img width="411" height="39" alt="image" src="https://github.com/user-attachments/assets/9670a279-0d58-418c-a16d-304585cb332e" />

Remove the directory "my-folder"

## COMMAND AND OUTPUT

<img width="490" height="104" alt="image" src="https://github.com/user-attachments/assets/e8950b96-c7ed-4a7f-851e-d8fc61778059" />

Create the file Rose.txt

## COMMAND AND OUTPUT

<img width="815" height="497" alt="image" src="https://github.com/user-attachments/assets/91d72773-bcd4-4c38-909d-02483629bfb9" />

Create the file hello.txt using echo and redirection

## COMMAND AND OUTPUT

<img width="498" height="158" alt="image" src="https://github.com/user-attachments/assets/da91d920-8254-4f62-964c-53b6b81f82bf" />

Copy the file hello.txt into the file hello1.txt

## COMMAND AND OUTPUT

<img width="528" height="136" alt="image" src="https://github.com/user-attachments/assets/56d1405e-c581-4531-8f10-93388eef0b51" />

Remove the file hello1.txt

## COMMAND AND OUTPUT

<img width="461" height="238" alt="image" src="https://github.com/user-attachments/assets/ac7a2516-3aa7-4d46-8b5d-0be8312ba114" />

List out the file hello1.txt in the current directory

## COMMAND AND OUTPUT

<img width="660" height="595" alt="image" src="https://github.com/user-attachments/assets/be59ce55-2518-454b-a163-768a9cd1f736" />

List out all the associated file extensions 

## COMMAND AND OUTPUT

<img width="557" height="246" alt="image" src="https://github.com/user-attachments/assets/042526cc-41ab-47d6-8544-9f44ec0a5791" />

Compare the file hello.txt and rose.txt

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT

<img width="422" height="134" alt="image" src="https://github.com/user-attachments/assets/34209f4f-238f-42ea-a409-fdffa91036d0" />


Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT

<img width="601" height="246" alt="image" src="https://github.com/user-attachments/assets/eb1fad0d-032e-4bc9-ac4d-f9f460670be9" />



Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT

<img width="409" height="168" alt="image" src="https://github.com/user-attachments/assets/3e1ccc0f-29ac-4512-ae54-e95fb046358c" />



Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT
<img width="631" height="241" alt="image" src="https://github.com/user-attachments/assets/615660ee-587a-4a44-b69c-a3c134c67df3" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="496" height="415" alt="image" src="https://github.com/user-attachments/assets/335961bd-d30f-47bb-877b-e350e3621248" />


# RESULT:
The commands/batch files are executed successfully.

