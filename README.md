# In This Project We Are Connecting ESP32 With Arduino :-                                                                                                               
# What is Arduino?                                                                                                                                                    
Arduino is an open-source electronics platform based on easy-to-use hardware and software.                                                                           
                                                                                                                                                                  
                                                                                                                                                                  
So in First step we need to installing Arduino  :                                                                                                                    
Second step:                                                                                                                                                           
open the Arduino and connect the ESP32 in USP your laptop ,                                                                                                             
the code is auto written found in the arduino we need just open ,                                                                                                       
file -> Examples -> Basics -> Blink 
                                                                                                                                                                      
<img width="960" alt="Blink code" src="https://user-images.githubusercontent.com/85851678/176401218-3f01640a-206c-43a4-895d-1a88e9e7cfcc.png">
                                                                                                                                                                      
<img width="960" alt="Arduino" src="https://user-images.githubusercontent.com/85851678/176402727-c5073106-6e69-46f7-805f-9bc63aa3f45c.png">
                                                                                                                                                                      
then choose the port because make sure the code is movement to the electronic chip ,                                                                                   
Tools -> Port -> COM6                                                                                                                                                   
Now the ESP32 will work .                                                                                                                                               
                                                                                                                                                                      
![WhatsApp Image 2022-06-29 at 12 49 14 PM](https://user-images.githubusercontent.com/85851678/176407430-3a1d9b19-2e66-410f-b059-ca40d84bf244.jpeg)
                                                                                                                                                                      
If not work , then we need to call the library ESP32 because you didn't installing the library                                                                         
Tools -> Boards Manager -> search ESP32 and installing                                                                                                                   
If not found the library 
<img width="960" alt="esp32 " src="https://user-images.githubusercontent.com/85851678/176417512-e9fdcbb2-ec47-4ba6-96a9-649e9d1a2f5a.png">

You must do this step :                                                                                                                                             
add URL the library from                                                                                                                                       
File -> Preferences -> https://dl.espressif.com/dl/package_esp32_index.json and go back to                                                                             
Tools -> Boards Manager -> installing ESP32  
 
<img width="960" alt="preferences" src="https://user-images.githubusercontent.com/85851678/176418356-fb375ea6-67ae-48ed-868a-ca57644f67b5.png">
                                                                                                                                                                     
<img width="959" alt="install esp32" src="https://user-images.githubusercontent.com/85851678/176418983-73f26202-b5c7-480d-92b2-e393eb492f9c.png">
                                                                                                                                                        
# Now will work the ESP .


# The problems:
The problems we encountered while doing this experiment is that the port is not defined                                                                             
                                                                                                                                                        
<img width="960" alt="image" src="https://user-images.githubusercontent.com/85851678/176435478-1ad4e0e1-f4d5-47c9-ae3e-bd11d557a638.png">
                                                                                                                                                        
* We have two solutions for this problem :                                                                                                                           
1- Tools -> Board -> ESP32 Arduino -> WEMOS D1 MINI ESP32                                                                                                           
                                                                                                                                                        
<img width="960" alt="tools" src="https://user-images.githubusercontent.com/85851678/176428794-5d0c0e12-3bee-4d0f-8d02-c3e582380774.png">
                                                                                                                                                        
                                                                                                                                                                     
 2-Update driver                                                                                                                                                     
My Computer -> Properties -> Devic Manager -> CP2104 Update driver                                                                                                 
If the problem didn't is solved, we go to Google and write CP2104 driver
                                                                                                                                                        
<img width="912" alt="solve probleam" src="https://user-images.githubusercontent.com/85851678/176431704-16e81e7a-93d3-4f48-badb-4e46562fff02.png">
                                                                                                                                                        
and Softwear Downloads  
                                                                                                                                                        
<img width="928" alt="solve probleam2" src="https://user-images.githubusercontent.com/85851678/176432034-4a8416c1-2158-46af-801e-e471fc6f9745.png">
                                                                                                                                                        
and back to Devic Manager -> CP2104 Update driver
                                                                                                                                                        
<img width="548" alt="solve probleam3" src="https://user-images.githubusercontent.com/85851678/176432414-ec15b556-e0eb-449f-a3d9-bf94f81c3f2e.png">
                                                                                                                                                        
<img width="547" alt="solve probleam4" src="https://user-images.githubusercontent.com/85851678/176432527-f57e2079-1db1-4b24-9145-223af83d8510.png">
                                                                                                                                                        
Enter the path where it was downloaded CP210                                                                                                                         
                                                                                                                                                        
<img width="548" alt="solve probleam5" src="https://user-images.githubusercontent.com/85851678/176432598-38ffeb25-288c-45f3-ac10-96879208926a.png">
                                                                                                                                                        
<img width="959" alt="port" src="https://user-images.githubusercontent.com/85851678/176435081-1df18382-0746-43f4-b444-3c580fd28e11.png">

