# Evaluation_Submission_Virik_Rana

----------------------------------------------------------------------------FINAL POC TASK------------------------------------------------------
 
 
Sensor Data collection system 

1.Create python app when arduino serially connected with raspberrypi show in app as device connected 
 

2.Authenticate with arduino device to read data from that by passing security key to arduino ,arduino should authenticate by checking security key from eeprom not from hardcoded in code. 
 

3.Once device authenticated then arduino should send dht temperature and humidity and motion sensor data to raspberrypi serially. 
 

4.Raspberrypi will collect data and store locally in local database. 
 

5.Raspberrypi will also stream real time data and show device status to thingsboard cloud. 



----------------------------------------------------------------------------FINAL POC 2------------------------------------------------------------

smart Intruder system :
(using raspberry pi,motion sensor and pi camera)

1. when motion detetct it, send notification to phone

2. pi camera capture  image and check what object it is using pretrained model

3. image will be captured and stored locally

4. that live image will be send to mail id 


-------------------------------------------------------------AWS EVALUATION TASK-----------------------------------------------------------


AWS Evaluation Definition : Use online dataset & find particular word from python application and return number of occurrence for that word
in python application by creating a rule and if word limit is > 100 then generate email notification




-----------------------------------------------------------AZURE EVALUATION TASK------------------------------------------------------------

Create a python application which uploads file on azure iot device and take the file name as device name and generates the device using DPS





----------------------------------------------------------------NRF EVALUATION TASK-------------------------------------------------------

 

button 1 pressed ,then broadcast beacon and in that change any value in ascending order for every 3 second. 

Button 2 Pressed ,then Stop Broadcasting Beacon. 

Button 3 Pressed , Get the last value of the Beacon Advertised last.



<!-- python definition -->
---------------------------------------------------------------- Python Definition ----------------------------------------------------------------
1. Create win lottery game app with python. - Admin can login into system.
- Admin can set one number for winning lottery game.
- Player user can register with name,number and password detials.
- After player login show welcome message "Hello name".
- there should be one play button in center of screen.
- when player pressed play button random number will show on untill 5 second and stop with last random number.
- if last random number equal to number set by admin then show message "you won with thumsup image" else show message "try your luck next time"



--------------------------------------------------------------------- C Definition-----------------------------------------------------------------
<!-- c definition -->
1. create encrypt document console app.

- admin login into app
- after admin login into app show 2 option
1. Create encrypted document
2. Decrypt Document.
- when user select 1 option then take user input data and convert that data into hex format and write to txt file and save it.
- when user select 2 option then user will enter path of file to decrypt that file from hex to normal text data and write into file.
- logout option for logout from app



<!-- cpp definition -->
---------------------------------------------------------------------------C++ Definition -----------------------------------------------------------------
  
  admin login
  show 3 options....
1.add new book
* admin select option 1 add new book into system(NAME , PRICE, Author DETAIL)

2.show all books
* admin select option 2 show all books and its details

3.Book allotment
* admin select option 3 show all books which is allotted and unallotted
* USER REGISTRATION using name, email,password...
* AFTER registration show login and user can login

Show following options after login
1 all books
* User choose option 1 show all books that are not allotted

2 Allot books
* take details about book name, date time , person details.

3 book allottment option
* show all allotted and unallotted option



--------------------------------------------------------------------------Raspberrypi----------------------------------------------------------------

Raspberrypi and Thingsboard(combine) Evaluation Definition

* Write softwrae for raspberrypi to control device from thingsbaord to allow raspberrypi to start rotating motor allow control from thingsboard to stop rotating motor. 
* also send device operating running status on thingbaord like "Motor running" and "stop running" mode.



-------------------------------------------------------------------------------Arduino-----------------------------------------------------------------

Arduino Evaluation Definition

* Write arduino firmware to when user send "GET Signal quality" sms text to arduino then retrieve Received signal strength indicator value of gsm module 
and send back sms with Received signal strength indicator value of devcie to user. if user send sms with "Turn on" to arduino then rotate motor at 90 degree angle 
and if user send sms with "Turn off" to arduino then rotate motor at 180 degree angle .
