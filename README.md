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
1a-) 	
1b-)	![IMG-20251001-WA0007](https://github.com/user-attachments/assets/00a3b8dc-7ef6-4fb5-add7-cc275b9150c7)
1c-)	![IMG-20251001-WA0006](https://github.com/user-attachments/assets/23d318ec-bf35-4a0e-863f-1f035516522d)
2.Camera permission is for flash warning (visually impaired) and 
SMS permission is for sending user-approved SMS to emergency contact during an earthquake.
Example for Step 2:![IMG-20251001-WA0010](https://github.com/user-attachments/assets/66d896fc-bbb2-4dbb-9294-0422752ec81a)
2a-)	![IMG-20251001-WA0004](https://github.com/user-attachments/assets/1e540d94-432c-4354-adce-5d2a46accfd2)

3.

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
