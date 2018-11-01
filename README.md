# Smart Nutritional Food Scale
This is a smart and portable food scale. Ideal for home kitchen use. Sensitive enough to weigh herbs and spices. They also have a wide range, so you can weigh heavy things like flour and rice.
It will enable people to weigh ingredients and snacks and then determine the exact amount of fat, proteins, carbohydrates and calories in the ingredients they’re using in recipes or the snacks they’re eating at home. The scales being useful for individuals with conditions such as diabetes to help them track their carbohydrates/calories intake. It will be also invaluable for dieters who track their food intake to achieve and maintain their weight loss goals. So many people use nutritional food apps, but without knowing the precise weight of the food being consumed, this information is less accurate.
It consists of a mobile app combined with a dedicated portable Bluetooth scale (Arduino 101 based), which together automatically calculate the exact amount of carbohydrates, proteins, fats and calories in a given meal, no matter where you are.
Resting on one side, the device act as a scale, displaying the weight of any objects placed on it on a LCD display. Flip the device (vertically standing), and the device will act as a cooking timer (e.g for baking purposes).


Features:-

•	Total Portability

•	Weighs up to 5kg

•	1g sensitivity

•	BLE 4.0 connectivity

•	Also acts as a Cooking timer


Working Video Link:- 
https://youtu.be/UpEkQ41bkfQ


<b>Hardware Screenshots of the project:</b><br>
Hardware Images.zip file (https://github.com/BJSingh/SmartScale/blob/master/Hardware%20Images.zip) contains the screenshots of the project.

<b>Arduino/Genuino Code for intelcurie 101:</b><br>
Download Smart Scale Arduino code zip file (https://github.com/BJSingh/SmartScale/blob/master/Hardware%20Images.zip) which contains ino file compiles in arduino IDE. Also copy or import libraries attached in zip file required for sensor(TH02 grove temp and humidity sensor) to your arduino libraries.


You can download the app from here:- 
https://github.com/BJSingh/SmartScale/blob/master/SmartScaleApp.apk


<b>Android App description:</b><br>
Android App made using cordova platform, you can find reference how to build on https://cordova.apache.org/docs/en/latest/guide/platforms/android/

App is made to connect Intel arduino 101 BLE board for smart scale project post on Devpost for intelHacks contest

Once you are done with setup of cordova platform then create project with plugin mention below. After this you can copy www folder and config.xml available here to your here project folder. Now build and run your android app.
Or directly you can use apk(SmartScaleApp.apk) file for testing. Allow permission needed for BLE.

BLE App reference
https://github.com/don/cordova-plugin-ble-central
https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/ArrayBuffer

Plugin Needed:
cordova-plugin-ble-central
