# publish.framework.coffee
publish coffee frame work
this framework supports communication between web brower and USB device.

## the current version
version 1.2

## supports USB vendor defined HID device.
## When "read" request is running(waits a data from device), If server receive "close" or "disconnect" request, server will execute "cancel" & "close" automatically. 
