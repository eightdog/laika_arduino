# laika_arduino
Arduino Board Manager Files

See www.project-laika.com for more information.

How to run Arduino on your Laika Explorer.

1) Having purchased the Laika Explorer Arduino kit you will have an Explorer board, an Arduino adaptor and the Arduino bootloader pre-installed.

2) Once you have built the Laika Arduino Adaptor please proceed as follows. Otherwise see the Laika Ardunio Adaptor build instructions.

3) Firstly, in the Arduino IDE enter/add the follwing to the File->Preferences->Additional Boards Manager URLs:

https://raw.githubusercontent.com/eightdog/laika_arduino/master/IDE_Board_Manager/package_project_laika.com_index.json

and restart the IDE.

4) Now go to Tools->Board->Board Manager and scroll down to select Laika and click install. (You will probably have to close and reopen the Board Manager for the Board list to be updated).

5) Connect power and USB and turn on your Explorer. Now in the Arduino IDE, go to Tools->Port and select the new com port that appears when the Explorer is turned on.

6) Download and run the example 'exploer_ex1' and test.
