# SmartMedicalAsssitantRobot
The proposal in this dissertation focuses on the main objectives as mentioned below:
1. To reduce the carrying load of the treatment details and the records.
2. To develop a centralized and distributed server and database where the 
information is shared between different servers
3. To provide assistance to patients at home quarantine when there is no one beside 
them.
4. To also intimate the relative of the patient and the nearest hospital so that they are 
there when needed.
5. Online patient health parameters monitoring

Working:
Upon entering the hospital premises, It instructs the patients to sanitize their hands 
using the sanitizer dispenser mounted on the back. The robot identifies and avoids obstacles 
using the ultrasonic sensor. Only after using the sanitizer, the patient is able to continue the 
process forward. This is done to prevent unnecessary spread of contagious viruses through 
the touch sensors present on the robot. The robot then reads the temperature of the patient 
using an DS1820 and asks the patient to place their finger on the Oximeter MAX30100 to 
collect important data regarding their heart rate, pulse rate and blood oxygen saturation level. 
Through the WiFi camera, the patients are then enquired about their travel history and present 
symptoms or allergy history. These data are collected using a voice & video recording 
camera module and are directly sent to the doctor. The doctors have live access to the patient 
and their data. An integrated storage compartment and tray are present on the robot for 
material handling and transfer of medicines or medical reports to the doctor or the patients. 
Figure 5 describes the working protocol of the medical assistant robot. Ultrasonic sensor is 
used for obstacle detection while robot in motion. If the obstacle range is less than2-3 feet, 
robot will stop to avoid collusion.
