# Parking-position-recording
A system that can record and access the position where the vehicles are parked. 
---
### Platform (current) 
iOS (version: anyone with Shortcuts app).   
### Tools     
#### Essential
- Shortcuts app on iphone
#### Optional
- NFC tag (hardware requirement: implement of the NFC module) 
---

> Reminder: There are two methods to access the position-recording function. One is developed with Shortcuts in Shortcuts app, and the other one is built with Automation in Shortcuts app. Due to some private settings, the program of the second method can not be uploaded to GitHub. Therefore, setting up the programm by yourself on your iPhone is needed for the second method.     


---
# Core Function 

## Setup
- Method one
  - Create a new folder in Notes.  
  - Open the iCloud link and set the name of the Notes folder in the **two blanks** with the name of the folder in Notes you just created.
  - check and set the privacy setting in the "i" sign - privacy in the down bar.  

- Method two  
  - Open Automation in Shortcuts app, go to the "+" sign on the top right and click "Create Personal Automation".  
  - Find the option: NFC, open it, click NFC Tag and scan the NFC Tag (Tip: put the NFC tag near the back camera of your iPhone where the NFC reader is).  
  - Create the position-recording program according to **Record the position**. 

---
## Record the position 
[iCloud link to the position-recording shortcuts](https://www.icloud.com/shortcuts/f6b5ec875ab5469c877a7cfd76184ed4)
  - record the current position (**varible 1**).  
  - open the current position in Maps and then take a screenshot (**varible 2**).  
  - choose from menu "Take a photo" (Yes/No).   
    -if yes, take a photo (**varible 3**), create note with photo,screenshot and current position in the folder you set in the setup process.
    (**Attention! the varible type of the current location has to be URL, otherwise the position would mess up. The type of the varible can be modified by click the varible and choose URL in the type option. **)。 
    
    
![2611678782808_ pic](https://user-images.githubusercontent.com/103753280/224952953-e50306b5-416c-4cd4-ac28-a66ed5b6300d.jpg)
![2621678782808_ pic](https://user-images.githubusercontent.com/103753280/224953048-19740621-3aa6-43b9-aafc-054446c82fae.jpg)



### Method to trigger the position recording

- Method one: shortcuts; triggered by icon on screen. 
  Click the share icon (the one with a square and an upwarding arrow) and choose "Add to Home Screen"
  Click the icon to run the program.   
- Method two: automation; triggered by a NFC tag placed near an iPhone.  
  To read the NFC tag, the screen have to light up. Running the program needs to unlock the iPhone.  
---
## Access the position 
(**Attention again! the varible type of the current location in the recording file has to be URL, otherwise the position would mess up. The type of the varible can be modified by click the varible and choose URL in the type option. **)。 
[iCloud link to the position-accessing shortcuts](https://www.icloud.com/shortcuts/dafc6d7916ff408fb1e4a37e5f9914a1)

![2651678786637_ pic](https://user-images.githubusercontent.com/103753280/224959468-66bcb0ff-57b0-4186-bb25-7c3de74b34d1.jpg)  

---
## Delete the files
(**Attention! this function might not working due to bugs on iPhone. I recommend deleting the files directly in Notes**).    
[iCloud link to the file-deleting shortcuts](https://www.icloud.com/shortcuts/017da0d67127422892aa36a11d286de1)
![2671678786864_ pic](https://user-images.githubusercontent.com/103753280/224960318-6fa9827f-3579-4bfe-ae3e-5ea1c699c63c.jpg)


