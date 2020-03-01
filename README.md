# WWM MobileChallenge

Hi guys!

After installing our hardware in thousands of cars we are in a hurry.

Our Operations Department has been asking for a new Master App for a while.

# TODO

This are their app specs:

- Implement an app where a user can see a table with all Bluetooth devices around.
- Table is sorted with WWM Hardwares on top.
- Table can be collapsed and expanded by clicking in the header.
- Just WWM devices are clickable.
- If user clicks on a WWM hardware we should connect to the device via bluetooth.
- Bluetooth connection is encrypted with AES-256.
- After connection, we should show map view.
- Map view is centered in user position.
- Map view shows mobile phone speed in real time.
- Button should change deppending on vehicle state.
- If user clicks in "play" button we should open the vehicle by sending a "power on" command. (Hint: intermittent light will appear in device).
- After powering on the vehicle, button should change to "stop" button.
- If user clicks in "stop" button, we should switch off the vehicle by sending a "power off" command.

## Bonus

- Start a timer since user clicks in start button until the vehicle is switched off. Then, reset timer.
- Having a fleet manager operating with the car is expensive so is important for us to estimate the cost. The cost starts from the power on until the power off. It is 0.13€/min.
- Animation for speed: 0 - 100 km/h

### Design



