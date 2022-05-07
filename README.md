### cddr-loadtest
#### The load test is created using python3 and locust.io framework
### pre-requisite
1. Install python3 plugin on IntelliJ or any preferred IDE. 
2. Install locust using command on terminal 'pip3 install locust'.

### Steps to run on Mac OS
1. Clone the repository on local machine. 
2. Edit the Authorization token in 'config.py' file 'get_token' method. 
3. Edit the test environment (dev/test) in 'config.py' file 'environment' method. 
4. Open the terminal and type in the folowing command to run 'locust -f IdeaProjects/LocustPerftest/src/locustperftest.py'. 
5. Open the browser and enter 'http://localhost:8089/' in address bar to open the locust UI. 
6. Enter the test parameters (Numbers of users, Spawn rate, host) and hit Start swarming.


### Steps to run on Windows 

1. Install Python 3 from [https://www.python.org/downloads/.](https://www.python.org/downloads/.) Make sure to check 
	"Add Python 3.10 to the PATH" checkbox .
2. Run "pip3  install locust" in the command prompt to install locust
3. Clone the repository on the local machine. 
4. Edit the Authorization token in 'config.py' file 'get_token' method. 
5. Edit the test environment (dev/test) in 'config.py' file 'environment' method. 
6. Open the terminal and type in the following command to run 'locust -f IdeaProjects/LocustPerftest/src/locustperftest.py'. 

	Note: If you get an error. Try to follow the below steps:
	
	a . Open  Windows PowerShell. Run following command:
	
    SETX  /M  PATH "%PATH%;C:\Users\Your Name\AppData\Local\Programs\Python\Python310"

	b. Next  run the following command 
	
    SETX  /M  PATH "%PATH%;C:\Users\Choudhury Iqbal\AppData\Local\Programs\Python\Python310	

   c. Restart your IDE.

8. Open the browser and enter 'http://localhost:8089/' in the address bar to open the locust UI. 
9. Enter the test parameters (Numbers of users, Spawn rate, host) and hit Start swarming.



