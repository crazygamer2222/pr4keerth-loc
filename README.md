---->>>Installation
---Kali Linux / Parrot OS 

$ git clone https://github.com/crazygamer2222/pr4keerth-loc.git

$cd pr4keerth-loc

$ chmod +x install.sh

$ ./install.sh

$ python3 prakeerth.py


--->>Start Ngrok Tunnel

$ ngrok config add-authtoken (YOUR_TOKEN)

$ ngrok http 8080 - copy the link and use 

python3 seeker.py -h

usage: seeker.py [-h] [-k KML] [-p PORT] [-u] [-v] [-t TEMPLATE] [-d] [--telegram token:chatId] [--webhook WEBHOOK]

options:
  -h, --help                          -  show this help message and exit
  
  -k KML, --kml KML                   -  KML filename
  
  -p PORT, --port PORT                -  Web server port [ Default : 8080 ]
  
  -u, --update                        -  Check for updates
  
  -v, --version                       -  Prints version
  
  -t TEMPLATE, --template TEMPLATE    -  Auto choose the template with the given index
  
  -d, --debugHTTP                     -  Disable auto http --> https redirection for testing purposes 
                                        (only works for the templates having index_temp.html file)
                                        
  --telegram                          -  Send info to a telegram bot, provide telegram token and chat to format =                                                   token:chatId separated by a colon
  
  --webhook                          -   Send events to a webhook endpoint to be processed
                                        Note : endpoint must be unauthenticated and accept POST request
                                      
