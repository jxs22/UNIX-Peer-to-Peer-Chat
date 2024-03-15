# Simple-Talk 

Simple-Talk is a chat-like feature that allows someone in one terminal to communicate with someone in another terminal. 

This program creates a UNIX process in UDP. 

## How to run it 

Both terminals will compile the program by typing "make". Then each user will run the program by entering a command in the following format: 

    ./stalk [my port number][remote machine name][remote port number]

So, if running in two terminals on the same machine, user 1 can enter: 

    ./stalk 6060 localhost 6001 

And user 2 can enter: 

    ./stalk 6001 localhost 6060 

## References 

Dr. Brian Fraser's operating systems workshops were referenced when constructing the socket and threads in this program. 

## Authors 

Preet Dhadda 
Jagjot Sidhu 
