# ESP32-using-http request
## Third task
Task: Use HTTP requests in ESP32 code to get data from a database.

This task involves connecting the ESP32 to a Wi-Fi network and periodically sending HTTP GET requests to a specified URL to retrieve and handle data. 

Here’s a brief explanation of the process:

1. Wi-Fi Connection: The ESP connects to the Wi-Fi network using the provided ssid and pass.
2. Serial Communication: It initializes serial communication to display the status and IP address once connected.
3. HTTP Requests: In the loop(), every 2 seconds (2000 milliseconds), the ESP sends an HTTP GET request to the URL "https://s-m.com.sa/r.html".
4. Response Handling: The code checks the response code; if successful, it prints the server's response to the Serial Monitor; otherwise, it prints an error message.
5. Purpose: The goal is to control the ESP remotely via the internet by sending different commands through HTTP requests.
#### I can experiment with the URL by changing the last letter according to my needs:
* Use "f.html" for the "forward" command.
* Use "b.html" for the "backward" command.
* Use "s.html" for the "stop" command.
* Use "l.html" for the "left" command.
* Use "r.html" for the "right" command.

#### This image shows you my experiment, where I used the link above, and it printed 'Right' on the screen:  

![image](https://github.com/user-attachments/assets/808848a8-a9ea-459f-ae94-fff1bd7ee979)

