The problem statement KVH-013 Tool for ground personnel tracking using NFC or other Technologies.
The devices and technology that we going to use in our project are as follows:
1) An Interface/website (with the help of language like JavaScript, PHP, SQL etc.)
2) Bluetooth module
3) NFC reader
4) IoT device
5) Android devices
The ground personnel officer must login to the website and enter the details asked along with the   unique ID of the NFC tag. The website will ask permission for GPS location, Biometric and camera of the device that officer is using to login.
There is various level of abstractions present in the website/interface.

The Highest level of abstraction is present at the officer or the user side in which he can go through only his own details.

The Middle level of abstraction is present at the commanding officer side in which he can monitor all the details of the officers assigned under him.

The lowest level of abstraction is present at the headquarters side. Headquarters have the permission to read and write the data (Basically make changes to the data). 

The project includes a proprietary IoT devices that is integrated with Bluetooth device and an NFC reader. The IoT device is connected with the mobile/android device of the ground personnel via Bluetooth. The NFC tag is constantly sharing signals to the NFC reader in the IoT device and further data transfer occurs between the NFC reader and the mobile device through Bluetooth. The mobile device is acting like a Transfer Module that is sharing the data to the server side from the user side. Every Ground personnel is equipped with these exchangeable Modules (IoT devices) that they can carry on their hip. 
These IoT devices are also Interconnected with each other, for example when the police officers are posted to the bandobast they are equipped with the IoT Modules that are interconnected and are constantly sharing data with each as well as the mobile device, these modules are acting as the nodes that are linked with each other. When the officer goes out of the assigned area, a warning signal is sent to the officer notifying him to return to the post. If the officer is unable to return to their respected post, another warning signal is sent to the officer and the party leader this time. If this officer breaks this protocol for the third time, now the notification is sent to the headquarter. The headquarter now can take appropriate actions towards them.   
There arises a problem that the module and mobile device can be handed over to other person. Officers will be asked to verify their biometric data using the two-factor authentication method embedded in the interface/application using the phone camera which will verify the likeness of an officer using an AI image processing model or using the fingerprint reader found in smartphones which can verify the biological data of the officer. Officers will be required to authenticate their identity at regular intervals during a bandobast. Officers cannot falsify identity or location by forfeiting the possession of NFC tags to another person.
