Three Level Password Authentication System.

This project is made to implement three levels of passwords for mainly windows folders to simply secure windows folders. So that no one can read or write on that folder directly without entering the password or simply without unloacking the folder.

This system have three levels of passwords showen bellow:

Level 1 Text Password
For text password it is a simple text based password to pass the level 1.
<img width="287" height="294" alt="LoginText" src="https://github.com/user-attachments/assets/59473be1-6839-46dc-bbd6-1daff682c8eb" />

Level 2 Color Combination

For Color Combination password there is basically three colors red green blue(RGB) where user can set different combination of colors by clicking on those colors.
<img width="429" height="316" alt="image" src="https://github.com/user-attachments/assets/ab8d52df-69dd-4e4c-a86c-582d694a0893" />


Level 3 Picture Password

For Picture Password there at first user have to select an image in jpg format to use as an password and then user can set the password by clicking on the image in different places, at the time of login the user have to choose the same picture he have choosen to take as an password and then user have to click at the same places where he/she have clicked at the time of setting the password
<img width="879" height="485" alt="image" src="https://github.com/user-attachments/assets/c3040449-2f90-43f5-b7ac-4485d79133b7" />

Then a folder locking system:

This is a simple folder locking system which user can operate just by browsing the folder he/she wants to lock then user can simply click lock to lock the folder or unlock to unlock the folder.
<img width="495" height="293" alt="image" src="https://github.com/user-attachments/assets/80934cc0-0811-405d-8e0e-1119af6e47b8" />

Advantages of this Application

.  This application provides the aditional security to the windows folders.
.  This application have an easy to use interface for interacting with this application.
.  It provides aditional security from the keyloggers because the keylogger can only work in the case of text password but there are two more passwords which are color combination and picture password.
.  It provides security to folders so that without unlocking the folder no one can delete, read, write, move or copy the folder.

To run this project for further development:

.    Download and install Visual Studio (community/any).
.    Open the Visual Studio with the admin privilege for FolderLock feature to run successfully.
.    Create your own local Sql database with three tables:-
.    Remember to keep names of tables as they are here!
.    LOGIN: USERNAME:varchar(50) PASSWORD:varchar(50) --no primary key
.    COLOR: val:varchar(MAX) --no primary key
.    picture: picture:int --no primary key
.    After that you need to copy the 'connection string' of the database you created.
.    Go to the main.cs file and paste the connection string you just copied in the format showen below:-
.    SqlConnection = new SqlConnection(@"Your Connection String");
.    Thats it now save all files and now you can run the project.
