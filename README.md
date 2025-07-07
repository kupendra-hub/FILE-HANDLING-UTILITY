# FILE-HANDLING-UTILITY

COMPANY : CODTECH IT SOLUTION 

NAME : KUPENDRA 

INTERN ID : CT04DG798

DOMAIN : JAVA PROGRAMMING

DURATION : 4 WEEKS

MENTOR : NEELA SANTOSH

FILE-HANDLING-UTILITY DESCRIPTION:
The task involves creating a Java program that can perform basic file operations: reading from a text file, writing to a text file, and modifying the contents of a text file. This is a fundamental skill in programming, as file handling is essential for many applications, including data storage, configuration management, and logging.

Key Components of the Program
Writing to a File: The writeToFile method takes a file path and content as parameters. It uses a BufferedWriter to write the content to the specified file. The try-with-resources statement ensures that the writer is closed automatically after the operation, preventing resource leaks. If the file does not exist, it will be created.

Reading from a File: The readFromFile method reads the content of a file line by line using a BufferedReader. It appends each line to a StringBuilder, which is efficient for string concatenation. The method returns the complete content of the file as a string. Error handling is included to manage potential issues, such as the file not being found.

Modifying a File: The modifyFile method allows for the modification of specific content within the file. It first reads the current content of the file, checks if the specified old content exists, and if so, replaces it with the new content. The modified content is then written back to the file. This method demonstrates how to perform search-and-replace operations on text files.

Main Method: The main method serves as the entry point of the program. It demonstrates the functionality of the other methods by writing initial content to a file, reading and displaying that content, modifying a specific part of the content, and then displaying the modified content.

Conclusion
This Java program effectively demonstrates basic file operations, which are crucial for many software applications. Understanding how to read, write, and modify files allows developers to create more dynamic and interactive applications. The program is well-documented, making it easy for others to understand its functionality and purpose. By mastering these file operations, developers can handle data more effectively, leading to improved application performance and user experience.

**OUTPUT**
[Task-1 output.txt](https://github.com/user-attachments/files/21105046/Task-1.output.txt)






