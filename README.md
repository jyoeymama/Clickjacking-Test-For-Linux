# Clickjacking-Test-For-Linux
This is a complitation of basic files on how to perform a basic iframe injection attack against any website. This is for educational purposes only! please don't abuse this!


HOW TO USE:

First to use this test, Git the clone

RUN THIS ON LINUX: git clone https://github.com/jyoeymama/Clickjacking-Test-For-Linux.git

then cd into the right directory

ALSO RUN THIS: cd Clickjacking-Test-For-Linux

Then change the script to the website of your choice
(Press Ctrl S to save the file then Ctrl X to exit)

Then locally host the service

RUN THIS COMMAND TO LOCALLY HOST A SERVER ON YOUR PC: python3 -m http.server 8080

Then on your browser of choice type this in: http://localhost:8080/clickjacking.html

Then if the website loads within the iframe it means its most likley vulnrable to clickjacking!
Hope this helps someone like it did for me!
Take care and have fun using my script!

