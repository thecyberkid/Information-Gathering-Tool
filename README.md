# Information-Gathering-Tool

Tool Overview:
This Python utility serves the purpose of precisely identifying the IPv4 Address of a specified
website. Users input the desired website as an argument when executing the script. The IPv4
Address retrieved can be seamlessly entered into a browser's address bar, ensuring a reliable
redirection to Google's website.

Output:
When we put the IPv4 provided here in any browser’s address bar we are getting redirected
to Google’s website.

Development Procedure:
Step 1: The tool begins by importing essential libraries, including "socket" for facilitating
network connections and "sys" for handling command-line arguments during runtime.
Step 2: The target hostname is dynamically extracted from the provided command-line
argument, making the tool adaptable to a wide range of web addresses.
Step 3: To obtain the IPv4 Address, the script calls the "gethostbyname" function from the
socket library, delivering the desired output.
