# WWM MobileChallenge

Hi guys!

After installing our hardware in thousands of cars we are in a hurry.

Our Operations Department has been asking for a new Master App for a while.

# TODO

This are their app specs:

1. Scan all Bluetooth devices around and show them in a table.
2. Table is sorted with WWM Hardwares on top.
3. Table has a header 

2. This table/view should be collapsed in a table header where we should be able to see the amount of BLE devices detected. Once they click on the header the list should be expanded or collapsed.
3. BLE devices on the list may have two designs. On the one hand, WWM devices should be clickable and with a enabled effect design. On the other hand, non-WWM hardwares should appear with disabled design and user interation is disabled.
4. Once the user cliks on a WWM device we connect to our device and open a new view with some info: show a MAP centered in user position, show current speed, button to interact with WWM device. We are very committed with security so BLE connection is encrypted with AES-256.
5. If user clicks on "Play" button, we need to send a "ON" command to WWM device (hint: red light will be shown). Afterwards, if the user clicks on "Stop" button, we need to send a "OFF" command to WWM device.

