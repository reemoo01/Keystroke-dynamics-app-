![My image](https://github.com/michasacuer/Keystroke-dynamics/blob/master/app/src/main/res/drawable/logo.png)

Keystroke dynamics, keystroke biometrics, typing dynamics and lately typing biometrics, is the detailed timing information which describes exactly when each key was pressed and when it was released as a person is typing at a  keyboard.

![My image](https://github.com/michasacuer/Keystroke-dynamics/blob/master/photos/5.jpg) ![My image](https://github.com/michasacuer/Keystroke-dynamics/blob/master/photos/7.jpg)

My Keystroke Dynamics is simple app to user recognition based on **REALESE TIME**. Classification based on kNN 
algorithm and Manhattan distance

# Why Realese time?

Because Android not provide any features for catching **KeyUp** and **KeyDown** events for Software keyboard. Key pressing time is more 
accurate, but its impossible to get it from default keyboard on Android device.

# Functionalities
- Login/Logout
- Registration
- Adding measures
- Classification
- Remember loged user on device
- English and Polish languages
- ROOM Database

![My image](https://github.com/michasacuer/Keystroke-dynamics/blob/master/photos/8.jpg) ![My image](https://github.com/michasacuer/Keystroke-dynamics/blob/master/photos/3.jpg) ![My image](https://github.com/michasacuer/Keystroke-dynamics/blob/master/photos/4.jpg)

# TODO:
- Add own keyboard with KeyUp and KeyDown events to more accurate measures (now i measure realese time only)
- More distances
- Changable "k" parameter
- Backend (probably ASP.NET with Identity)
