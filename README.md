# cheri
cheri is a proof of concept Python script that interacts with ChatGPT to determine if Python bytecode is malicious, suspicious, or safe.


cheri is not always 100% accurate. Please keep this in mind. Whenever cheri is not sure about a file, it will be labeled as suspicious. 
Run cheri multiple times for a clearer picture.
cheri will input a .pyc file called "input.pyc" and once given it will create a txt file called "input.txt" filled with the Python bytecode.
cheri will not delete the input.txt file after analysis. 

cheri has three outputs: malicious, suspicious, and safe. If any other output is given it sould not be considered an output.
