# BeaconTest

### Overview:
Quick hack: iOS app, broadcasts device's `UUID`.

There is second app which listens for specified `UUID`.
[BeaconTestReceiver](https://github.com/knowbody/BeaconReceiverTest)


### Instructions:
Make sure you test them on the actual device, as Apple dropped `CoreBluetooth` in the simulator. 
 - Touch broadcast button (the app will start broadcasting)
 - and then on [BeaconTestReceiver](https://github.com/knowbody/BeaconReceiverTest) app you should see the message "Beacon found!"

### Details:
![alt tag](http://i60.tinypic.com/s6ouiq.png)
