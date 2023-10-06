# Socket Programming - Task 1
## General Instructions
- This activity is to be completed in pairs. Sign up your pair using the People Tab --> Programming Pair. For those who did not sign up, it is assumed that you will do your task alone. 
- Use the provided .java source files (CSNETWKClient.java Download CSNETWKClient.javaand CSNETWKServer.java Download CSNETWKServer.java) for this activity if you were not able to code during the class demonstration.
- Threading and GUI are not required for this activity.
- The tasks are independent of one another. You must use the base source codes when working on each task.
- Lab Activity Template: _4shareLinks to an external site.

## Requirements

![image](https://github.com/jordanchong911/Lab03/assets/94843916/f359a9da-865c-4306-92aa-e7f2b5e1d72e)

Modify the source codes so that the client will download a non-empty text file called "Download.txt" from the server after connection has been established. The downloaded file will be saved in the same directory as the client application and will be named as "Received.txt."

### Arguments
For the Server application, the following argument is required:
- Port number (**args[0]**) – the port number that the server will listen on for incoming client connections
For the Client application, the following arguments are required:
- Server hostname/IP address (**args[0]**) – the hostname/IP address of the server the client will connect to (must use localhost or 127.0.0.1)
- Port number (**args[1]**) – the port number of the server the client will connect to

### Notes
- The "Download.txt" file must be placed in the same directory as the source files so that the path is not needed anymore.
- For uniformity and easier checking, the filenames of the text files ("Download.txt" and "Received.txt") should be hardcoded for this activity.
- This task will require additional classes especially those needed for reading and writing files. Include said classes accordingly.
  - However, the existing classes used (ServerSocketLinks to an external site., SocketLinks to an external site., DataInputStreamLinks to an external site., and DataOutputStreamLinks to an external site.) during the class demo must not be removed nor replaced. The reading and writing of files can be linked to the DataInputStreamLinks to an external site. and DataOutputStreamLinks to an external site.
- Although the sample run shows events in sequence, some print statements will appear together as soon as the client is connected to the server.

### Sample Run
1. Run the Server application to listen on the indicated port number.

![image](https://github.com/jordanchong911/Lab03/assets/94843916/e8cfdfd8-27e2-482d-b687-610f40c6e6eb)

2. Run the Client

![image](https://github.com/jordanchong911/Lab03/assets/94843916/cc6f81e6-25b4-4501-916d-c0c4cc5a3c25)

3. Once connection has been established, the client will download the “Download.txt” file from the server and save it as “Received.txt.”

![image](https://github.com/jordanchong911/Lab03/assets/94843916/1c166685-f4da-4110-ab30-d0b71bad3ce2)

Sample “Download.txt” file content

![image](https://github.com/jordanchong911/Lab03/assets/94843916/5c38af38-bfdb-4fb6-88c2-7cf09a6dcfce)

4. The client will receive confirmation that the file has been downloaded successfully.

![image](https://github.com/jordanchong911/Lab03/assets/94843916/5aa5f412-308c-486c-a9b5-9ea66374efb2)

Sample “Received.txt” file content

![image](https://github.com/jordanchong911/Lab03/assets/94843916/116ca6f4-9a04-46e4-aca8-1f82de9987b6)

5. Connections and applications will be terminate

![image](https://github.com/jordanchong911/Lab03/assets/94843916/b771de58-4724-4b1f-8ccd-9f54ad290cac)


### Submission
- Submit the two .java files (not .class) on the designated assignment page on or before the deadline indicated.
- Include a comment block on each source file indicating the group member names.
- The filename for the Server source code is FileServer.java
- The filename for the Client source code is FileClient.java
- Filenames and Class names for the source codes must be the same.
- Include screenshots of the activity to signify that you have run your code successfully.
- Source files will be compiled by the instructor using CLI during checking. Files that did not compile properly will not be given credit.
