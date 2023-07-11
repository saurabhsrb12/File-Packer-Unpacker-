# File-Packer-Unpacker-
Marvellous Packer-Unpacker is a Java-based GUI application that allows users to pack files into a single archive file and unpack files from the archive. The application provides an intuitive graphical user interface for easy file packing and unpacking operations.
.
Features=====================================================
File Packing: Users can select a directory and provide a destination file name to pack all the files within the directory into a single archive file.
File Unpacking: Users can specify a packed file and provide a destination directory to extract the files from the archive.
User Authentication: The application includes a login screen that requires users to enter a username and password to access the main functionality.
Clock Display: The GUI displays the current date, time, and day for easy reference.
.
Prerequisites=================================================
Java Development Kit (JDK) installed on the system.
An Integrated Development Environment (IDE) such as Eclipse or IntelliJ IDEA (optional).
.
Getting Started==============================================
Clone the repository or download the source code files.
Open the project in your preferred IDE (optional).
Build the project to compile the Java classes.
.
Running the Application======================================
Open a command prompt or terminal window.
Navigate to the project directory.
Run the following command to execute the application:
bash
Copy code
java MarvellousMain
The application will launch, displaying the login screen.
Enter the username and password to log in (Username: MarvellousAdmin, Password: MarvellousAdmin).
After successful login, the main page will be displayed, providing options to pack files or unpack files.
.
.
Usage=====================================================
File Packing==============================================
On the main page, click on the "Pack Files" button.
In the "Directory name" field, enter the path to the directory containing the files you want to pack.
In the "Destination file name" field, enter the desired name for the packed archive file.
Click the "SUBMIT" button to initiate the packing process.
Once the packing is complete, a success message will be displayed.
.
File Unpacking==========================================
On the main page, click on the "Unpack Files" button.
In the "File Name" field, enter the path to the packed archive file you want to unpack.
Click the "Extract Here" button to start the unpacking process.
The files will be extracted to the same directory as the packed file.
Once the unpacking is complete, a success message will be displayed.
.
Limitations==============================================
The application currently has a hardcoded username and password for simplicity. Modify the code to implement a proper user authentication system.
The code provided is a partial implementation, and some parts may be missing or incomplete. Extend and modify the code as per your requirements.
.
Contributing=============================================
Contributions to the Marvellous Packer-Unpacker project are welcome. If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.
