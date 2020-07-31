# How to remove Zigbee Devices


## Principle

When a device is paired this imply that the device is known in several locations:

1. known by the ZiGate 
1. known by the plugin ( one entry by device )
1. known by Domoticz ( one or multiple widgets are related to the same device)

In order to get a device fully removed , you need to make sure that device is removed on all 3 locations.

### Attention

By default, the plugin is configured to not request the device removal from Zigate. If you want to activate this feature, you have to enable the flag "Removal on ZiGate" from the Web UI Admin.

![Removal On Zigate](https://github.com/pipiche38/Domoticz-Zigate-Wiki/blob/master/Images/EraseDeviceOnZigate.png)

## Removing End devices ( battery ) 

There is no automatic way to get most of the end devices removed from the Zigate.  To make sure you get the device removed from ZiGate, here is a step approach to follow.

1. Make sure ZiGate is not in "Permit to Join mode", so "Accept new Hardware " is disabled in the WebAdmin UI and the ZiGate doesn't blink blue.
1. Reset the end device
1. you should receive a leave message like that one `Status: (DIN-ZiGate)  (d009/00158d0002722c67) send a Leave indication and will be outside of the network. LQI: 0`
1. Remove all Widets from Domoticz

That's it.


## Removing Router devices ( main powered )

Usally with Main Powered device, you can remove all associated Widgets from Domoticz, and while removing the last one, (if the "Removal on ZiGate" parameter is enabled), the plugin will request the device to leave.


A message like that should be received by the plugin and visible in the log as a "Status"

```
Status: (DIN-ZiGate)  (d009/00158d0002722c67) send a Leave indication and will be outside of the network. LQI: 0
```

If you don't get such message, you just need to apply the same procedure as the one presented for the End Devices

