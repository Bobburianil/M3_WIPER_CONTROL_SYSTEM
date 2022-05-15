# HIGH LEVEL TEST PLAN 
 
<html> 
<body> 
<!--StartFragment--> 
 
Test ID | Description | Input | Expected output | Actual Output | status 
-- | -- | -- | -- | -- | -- 
01 | Ignition On |  Pressing Button 1st 2sec  | key status | Key Status Displayed |✅ 
02 | Wiper On | Pressing user button once | Wiper Status-1Hz | Wiper Status Displayed |✅ 
03 | Wiper On | Pressing user button twice | Wiper Status-4Hz | Wiper Status Displayed |✅ 
04 | Wiper On | Pressing user button thrice | Wiper Status-8Hz | Wiper Status Displayed |✅ 
05 | Ignition Off | Pressing Button 1st 2sec  | Ignition key status | key status Displayed |✅ 
 
<!--EndFragment--> 
</body> 
</html> 
 
 
# LOW LEVEL TEST PLAN 
 
<html> 
<body> 
<!--StartFragment--> 
 
Description | Input | Expected output | Actual Output | Status 
-- | -- | -- | -- | --  
ignition_on() | User Button Press 1st 2sec | RED LED ON | RED LED ON | ✅ 
LED cycle | Button Press once | All LEDs ON | All LEDs ON | ✅ 
LED cycle | Button Press twice | All LEDs ON | All LEDs ON | ✅ 
LED cycle | Button Press thrice | All LEDs ON | All LEDs ON | ✅ 
ignition_off() | User Button Press 2nd 2sec | RED LED OFF | RED LED OFF | ✅ 
 
<!--EndFragment--> 
</body> 
</html>


# **OUTPUT IMAGES**

![output](https://user-images.githubusercontent.com/101082480/168464377-a2113289-8dda-4e06-ae8a-93c325133939.jpeg)
![outut1](https://user-images.githubusercontent.com/101082480/168464437-059a25b4-ea91-49ed-a6ee-bc3a20757a14.jpeg)
![output2](https://user-images.githubusercontent.com/101082480/168464453-e3ce514c-edac-4d72-a1f5-ecb4dcdcc121.jpeg)
![output3](https://user-images.githubusercontent.com/101082480/168464465-0b019efa-240c-43c1-87cd-be75325cba53.jpeg)
![output4](https://user-images.githubusercontent.com/101082480/168464477-60cc141c-b56d-4c68-9e7b-22b811edef65.jpeg)
