# skibbleJMeter
 Non-GUI mode

 -For Windows:
Go to “Start”
Search “Run” Or Press “Win+r”
Navigate to ‘bin’ folder of JMeter using “cd” command
Type the command:
jmeter -n -t <jmx file name with path> -l <log file name with path>
jmeter -n -t <jmx file name with path> -l <log file name with path> -e -o <path of folder to save HTML report>

 -For Unix:
Navigate to ‘bin’ folder of JMeter using “cd” command
Type the command:
./jmeter.sh -n -t <jmx file name with path> -l <log file name with path>

Unix’s command to generate an HTML report after the completion of the test:
./jmeter.sh -n -t <jmx file name with path> -l <log file name with path> -e -o <path of folder to save HTML report>