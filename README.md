Key-logger : Capturing Keystrokes

AGENDA
Keyloggers hold paramount significance in cybersecurity as essential tools for threat detection, prevention, and user behavior analysis. These discreet applications monitor and record keystrokes, enabling the identification of potential security breaches, insider threats, and anomalies in user activities. Crucial for digital forensics, keyloggers aid incident response, enhancing the overall resilience of systems. By facilitating password security, compliance monitoring, and real-time threat detection, keyloggers contribute to proactive cybersecurity measures. While their relevance is undeniable, responsible deployment is imperative, ensuring ethical use, user privacy, and compliance with legal regulations.

PROJECT  OVERVIEW
A keylogger is a type of software or hardware device that can capture or record every keystroke made on a computer or a mobile device.
This project helped me :
Understand the Basics of a keylogger
Understand how to access the keystrokes from a system
Understand the process of storing the accessed keystrokes into a file
Implementation of keylogger
Basics of Python GUI

WHO ARE THE END USERS OF THIS PROJECT?
The end users of a keylogger project in the cybersecurity domain can vary depending on the specific use case and intended application:
Corporate IT Security Teams: The keylogger can be used as a tool for monitoring employee activities on company devices, helping to identify and respond to suspicious behavior or security breaches.
Parents/Guardians: Parents can use the keylogger to keep track of their children's online interactions, identify potential risks, and promote a safe digital environment.
Educational Institutions: Educational institutions can use the keylogger to monitor student activities on school-provided devices, prevent misuse, and address any potential cybersecurity issues.
Individuals for Personal Security: Individuals can use the keylogger as a personal security tool to monitor their own devices, detect potential unauthorized access, and take preventive measures against identity theft or unauthorized use.

SOLUTION AND ITS VALUE PROPOSITION
The keylogger captures a comprehensive log of keystrokes, providing valuable insights into user activities.The solution is versatile, making it applicable in various scenarios such as corporate environments, parental control, and educational institutions. By offering real-time tracking of pressed, held, and released keys, our solution allows for instant detection of any suspicious or unauthorized activities. I prioritize security by implementing a secure logging mechanism that stores the captured data in both a text file and a JSON file, ensuring ease of analysis while maintaining data integrity. The intuitive graphical user interface built with Tkinter makes the solution accessible and easy to use for individuals with varying technical expertise.

INSTRUCTIONS:
 
Step 1:
Ensure you have Python installed on your system. You can download it from python.org.
Step 2:
Open your terminal or command prompt and install the necessary libraries using the following commands:
"pip install pynput"
Step 3:
Download the keystroke tracking program, "KeyLogger.py" and extract the file to a folder of your choice.

Step 4:
To use the program navigate to the folder containing the program and double click it or open the file in 
the the python IDLE and run it. 

Step 5:
A GUI window will appear with "Click START to begin keylogging." displayed. Click the "Start" button to initiate the keylogger.

Step 6:
The program is now actively recording keystrokes. The GUI will display "[+] Keylogger is running!".

Step 7:
To stop the keylogger, click the "Stop" button. The program will display "Keylogger stopped."

Step 8:
Check the program folder for two log files:

key_log.txt: Contains a chronological record of keystrokes.
key_log.json: Provides a structured JSON format of the keystrokes.
