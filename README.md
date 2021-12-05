# CIS389WebServer
CIS389 Final Project
Java HTTP(Web) Server

## Authors
- Yuhao Chen 
- 

## Functionalities
- Handle GET/HEAD/POST Request
- TO BE ADDED
- 

## How to run the server
### Compile JHTTP.java  
`javac JHTTP.java`   
### Run JHTTP   
In the terminal, type the following:  
`java JHTTP XXX 888`  
Replace 'XXX' with the root directory of the webserver  
If you get this from GitHub, all the html files are in /CIS389WebServer  
In my case, I replace 'XXX' wiht `~/Documents/GitHub/CIS389WebServer`  
You should have the same format `PATH_TO_THE_PROJECT/CIS389WebServer`  
In my case, the run command is  
`java JHTTP ~/Documents/GitHub/CIS389WebServer 888`  
I picked port number 888, but you can choose others as well (make sure no conflict)  

## How to test GET/HEAD/POST Requests
Open the web browser, Firefox, Google Chrome, etc.  
Type the following URL (make sure the port numbet match the one you used to run the server)   
`http://localhost:888/`   
It will automatically navigate to `http://localhost:888/index.html` 

### Test GET/POST Request
(If you are using Firefox, you can get the HTTP HEADER LIVE to see the request and reponse)  
Type the following URL in your browser  
`http://localhost:888/form.html`  **(Send GET Request)**  
It will show you an HTML form  
You can enter the name and city, click on Submit  **(Send POST Request)**  
See the response from the HTTP Server for the POST request   
