# bluetooth_test_2

a simple bluetooth chat application (with bad UI pls don't judge) taking inspiration from [google's offical bluetooth repo](https://github.com/android/connectivity-samples/tree/main/BluetoothChat), 
and this [amazing repo](https://github.com/mitchtabian/Sending-and-Receiving-Data-with-Bluetooth) as well, and of course the [official docs](https://developer.android.com/guide/topics/connectivity/bluetooth)  
Note: When testing for 2 devices make them both discoverable, and then click on the names of each devices in the list view of both devices simultaneously so the 
AcceptThread in the BluetoothConnectionService.java file runs on both devices and then the connection can be started by clicking start connection on either device and then the messages can be sent  
for future use: [bluetooth low energy](https://developer.android.com/guide/topics/connectivity/bluetooth/ble-overview) i.e when battery of device is low. Also need to update the display of messages to erase the previous messages

