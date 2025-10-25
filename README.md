TRS4R3N ShindoAlert

Powered by JMA (Japan Meteorological Agency)

TRS4R3N ShindoAlert is an Android application developed to enhance earthquake safety in Japan and quickly inform the public in emergency situations.

⸻

Features
	•	Real-Time Earthquake Data:
All information from the Japan Meteorological Agency (JMA) is listed under a map.
	•	Interactive Map:
	•	Red markers: Earthquakes
	•	Green marker: User’s location
	•	Earthquake Detection and Emergency Alerts:
	•	Phone sensors detect shaking.(accelerometer)
	•	Data is compared with JMA records; if none exists, the shaking data is analyzed.
	•	If the earthquake magnitude exceeds 4.0 Mw:
	•	SMS screen opens and sends location-based messages to emergency contacts.
	•	Alarm + vibration + flash alert is triggered (optimized for people with disabilities).
	•	Mirror Screen allows display on TV.
	•	Wi-Fi printing allows earthquake reports to be printed.
	•	119 emergency call button for quick access.
	•	Battery Emergency Mode:
If battery drops below 20%, the emergency SMS screen automatically opens.
	•	Offline Mode:
When internet is unavailable, the app stores the latest JMA data locally for continuous access.
	•	Emergency Contact Registration:
	•	Requests SMS permission.
	•	Users enter name and phone number to register contacts.
	•	At least one emergency contact must be registered.
	•	Single tap edits a contact, long press deletes.

⸻

Technologies Used
	•	Android (Java)
	•	Kotlin (build.gradle)
	•	Google Maps API
	•	REST API integration
	•	Mirror Screen (Chromecast, Miracast, DLNA)
	•	Wi-Fi Print integration

⸻

Installation & Usage
	1.	Install the APK on your Android device.
	2.	Grant SMS and location permissions when prompted.
	3.	Register at least one emergency contact.
	4.	Alerts are automatically triggered when an earthquake is detected.
	5.	For Mirror Screen and Wi-Fi Print, select the appropriate devices.

⸻

Usage Steps;

1.When the application is first opened, it first directs you to the emergency contact adding page. Here, the emergency contact's name, surname, and phone number are added. After adding the contact, it is saved through the "Contact Added" popup. Then, with a single click, it is possible to edit it, with a long press, it is possible to delete it (with user approval). Adding one contact is mandatory. (The data stored in the white rectangle is personal information).
Example for Step 1:

Add Emergency People Name&Surname![IMG-20251001-WA0001](https://github.com/user-attachments/assets/ca373e47-e76f-4665-8277-f2bfb100d9c3)

Add Emergency People Phone Number![IMG-20251001-WA0002](https://github.com/user-attachments/assets/7f400877-0df1-416a-a821-093adcf44d6d)

Edit Emergency People Name&Surname And Phone Number![IMG-20251001-WA0006](https://github.com/user-attachments/assets/23d318ec-bf35-4a0e-863f-1f035516522d)

2.Camera permission is for flash warning (visually impaired) and 
SMS permission is for sending user-approved SMS to emergency contact during an earthquake.
Example for Step 2:

Check Camera Permissions For Flash Alarm![IMG-20251001-WA0010](https://github.com/user-attachments/assets/66d896fc-bbb2-4dbb-9294-0422752ec81a)

Check SMS Permissions For Send Emergency People Alerted Earthquake!![IMG-20251001-WA0004](https://github.com/user-attachments/assets/1e540d94-432c-4354-adce-5d2a46accfd2)

3.After adding an emergency contact, we return to the main screen of the application with the back button. Here, we are greeted by Google Maps and a list below it. The red markers on the map show the earthquake, the green marker shows the user's location. Data from JMA (Japan Meteorology Agency) is listed, and then we can print it if we want by selecting an item from the list (Wi-Fi print).

Application Main Screen Red Marker(Earthquake) Green Marker(User Location) And Listed  JMA Data![IMG-20251001-WA0008](https://github.com/user-attachments/assets/697d7cab-5f88-4b60-90a5-d3f811c54485)

Earthquake Data Displayed When Clicked![IMG-20251001-WA0011](https://github.com/user-attachments/assets/f40b7214-5e27-4e8f-864c-643a2e172539)

4.Finally, when an earthquake is detected, JMA data and the phone's accelerometer are used. First, the earthquake condition is checked. If it's not, it's perceived as a false alarm and isn't triggered. However, if it's >4.0, it first examines the JMA data to see if there's been an earthquake in the area that's experienced it before. If not, it detects it as a new earthquake and displays a warning message to the user. It provides earthquake information such as intensity, magnitude, and depth. Three options are available: 1. Mirror Screen (so you can follow along with your family on your TV). 2. Print (printing details as evidence for emergency services). 3. 119 (Japan Emergency Line) is user-approved. Meanwhile, if the battery is <20%, the "I'm safe" + location information is sent to the emergency contact. In case you're offline, the data is stored in the cache while you're online, keeping you up-to-date when offline.

Automatically opens the SMS screen of the emergency contact when an earthquake is detected (user approved)![IMG-20251001-WA0009](https://github.com/user-attachments/assets/93509e96-ce68-44aa-b27a-6dbfb136dcfb)

>=4.0mW When it detects an earthquake, it works as a combination of flash + vibration + alarm and when you return to the application, the earthquake information on the screen is displayed from left to right as "Reflect on Screen","Print","Call 119" ![IMG-20251001-WA0012](https://github.com/user-attachments/assets/05e31104-c40b-4593-801a-3beacafce184)

A Mirrored View Of The App On A Television![IMG-20251001-WA0013](https://github.com/user-attachments/assets/653e4de6-97b9-4d34-b0c2-875284ccacdb)

Printer Details ![IMG-20251001-WA0014](https://github.com/user-attachments/assets/611070c6-e4d1-490c-b3b5-15b548cfb47c)

Print Details On Paper![IMG-20251001-WA0015](https://github.com/user-attachments/assets/d4f2f5bb-4357-44b1-b401-8b10753132a7)


Project Resources
	•	JMA Data Source: https://www.jma.go.jp/bosai/quake/data/list.json

⸻

Contributors
	•	Serhan Kırca – Project design, software development, user experience

⸻

License
	•	MIT License (All code and documentation)

⸻

Project Mission

“With TRS4R3N ShindoAlert, my mission is to contribute to a safer and more resilient Japan.
Earthquakes may be inevitable, but fear doesn’t have to be.”

This application is developed to enhance public safety and emergency information dissemination in Japan.
