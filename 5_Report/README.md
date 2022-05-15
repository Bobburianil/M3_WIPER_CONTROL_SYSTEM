# **Wiper Control System**

## **1 About Wiper Control System**

## **1.1 Abstract**

A wiper is a necessary component that cleans raindrops or any other liquid off the vehicle's windscreen. The prior system required manual wiper activation, and the operation of bringing up the wiper was difficult to manage. As a result, this system is proposed to address these issues. The goals of this project are to provide wiping systems for older cars, to improve the system by employing actuators and pull switches (using the same switch for multiple purposes by stepwise switching), and to regulate the engine and wiper speed with a single switch.

## **1.2 Description**

Wiper Control System is an electronic device that replaces the traditional wiper blade in automobiles. In this system, we will use a single switch to control the ignition button (on the motor) in the ACC position. As a first press, turn on the wiper system by pressing the button a second time, change the wiper speed by pressing the button a third time, and turn off the motor by pressing the button a fourth time. All of this was accomplished using LEDs in a simulation tool.

## **1.3 Features**
  - ON The Motor(Ignition Position)
  - OFF the Motor
  - Power ON Wipers
  - Speed Controll of wipers

## **1.4 SWOT Analysis**
  ![image](https://user-images.githubusercontent.com/101035721/168051944-525000fb-171d-4984-ab8e-7b1a4ec9c0d5.png)

  ## **1.5 5W's & 1H**
  ![5W1H Chart](https://user-images.githubusercontent.com/101035721/168054091-7c5eb964-7c75-4e84-b213-aada6aabc571.jpg)

  ## **2 Requirements**

  ## **2.1 High level Requirements**

  <html>
<body>
<!--StartFragment-->

ID | Description
-- | --
HLR-1 | User shall be able to ON the motor
HLR-2 | User shall be able to ON the wipers and controll the speed of wipers 
HLR-3 | User shall be able to OFF the wiper
HLR-4 | User shall be able to OFF the motor

<!--EndFragment-->
</body>
</html>

  ## **2.2 Low level Requirements**

<html>
<body>
<!--StartFragment-->

ID | Description
-- | --
LLR-1 | When user presses the switch for first time for two seconds, The Red LED is ON
LLR-2 | When user presses the button twice,  Blue, Green and Orange LEDs come ON one at a time with the set frequency, The frequency changes on every alternate key press, 3 frequency levels with 1, 4 and 8 Hz
LLR-3 | When user presses the button  fourth time The LED glow pattern stops 
LLR-4 | Again pressing the button for two seconds The Red LED is OFF

<!--EndFragment-->
</body>
</html>

# **1 Behavioural Diagrames**

## **1.1 High Level Flow Chart Behavioural Diagram**
![image](https://user-images.githubusercontent.com/101035721/168064915-51deb595-8240-42c5-a672-4f827d4366d0.png)

## **1.2 Low Level Diagrames**
![image](https://user-images.githubusercontent.com/101035721/168068643-54546953-ee1f-4601-a446-25e08b592789.png)

## **Schematic Diagramme**
![image](https://user-images.githubusercontent.com/101035721/168410775-7d0c6384-56ed-4957-b64e-789317acf299.png)

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

![photo_2022-05-14_10-35-29](https://user-images.githubusercontent.com/101035658/168411780-85ceb31f-dbbc-4c14-ae01-5dbc8445adcb.jpg)

![1 3](https://user-images.githubusercontent.com/101035658/168411717-9fbd2982-7714-4823-b76f-bcbfead5c014.jpg)

![1 6](https://user-images.githubusercontent.com/101035658/168411757-99b6207d-f961-4ea3-aeeb-11d38c6190f4.jpg)

![1 4](https://user-images.githubusercontent.com/101035658/168411715-de195ad6-be5c-4b78-a796-84a4938f9c92.jpg)

![1 2](https://user-images.githubusercontent.com/101035658/168411718-58d5b9da-4e82-444d-a0ed-2113f8d969ed.jpg)

