# TCP-PORT-SCANNER-PYTHON
A python based TCP port scanner featuring 8 different scans.
Refer to the 8 scans performed : [8 Scans PPT](https://github.com/smsraj2001/TCP-PORT-SCANNER-PYTHON/blob/main/THE%208%20SCANS%20PERFORMED.pptx)

## SYNOPSIS
This python project presents 7 TCP scans and 1 UDP scan.
## DESCRIPTION
- Scans can be performed by entering ```Target IP address``` and entering the ```Port number```.
- Port numbers can be entered as a single number, a list or a range.
- Output in 30 seconds to 1 minute. (Usually the time taken will depend on the system and internet connection)

## INSTRUCTIONS

- Requires ```Python2``` version preferably ```python 2.7```
- Also requires a ```Linux``` environment such as WSL, or linux OS in VBox, or actual Linux OS, etc...
- After the above 2 rquirements, run the following command for help :-
```bash
sudo python2 TCP_PORT_SCANNER.py -h
```
- Demonstrating the port arguments
  - -p (single port number), 
  - -pl (list of port numbers separated by commas), and 
  - -pr (port range of form a-b)
- Command to run the above variations(All variations can run independent of each other!!!) :-
```bash
sudo python2 TCP_PORT_SCANNER.py <IPV4 address> -p <Single port number> -pl <Of form a,b,c> -pr <Of form a-b>
```
- Some examples :-
```bash
sudo python2 TCP_PORT_SCANNER.py 8.8.8.8 -p 80 -pl 53,853 -pr 441-444
```
```bash
sudo python2 TCP_PORT_SCANNER.py 8.8.8.8 -pr 441-444
```

- For further Demo and use of this project, please refer to the PDF file attached : [REFERENCE WORKING.pdf](https://github.com/smsraj2001/TCP-PORT-SCANNER-PYTHON/blob/main/REFERENCE%20SCREENSHOTS-TCP%20PORT%20SCANNER.pdf) 

#### ```NOTE``` : For any queries/suggestions, please feel free to contact : sutharsanraj2001@gmail.com
