# Jasco Switch Double Taps

**Version: 1.0**

Create automations to react to double taps from supporting Jasco switches.

The Jasco switches that support the use of double tap are currently not triggering events in ZWave-Js.  However using the "zwave_js.value_updated" trigger in home assistant it is still possible to offer double tap functionality on these switches.

      

**Requirements:**
  - ZWave-JS
  - Jasco Z-Wave switches that support "Double Tap" functionality.  I personally have had luck using 14321 / ZW3005  with firmware 5.29.
  - "Group 3" of the switch must be set to include your controller device. You will probably need to use the community version of ZWave-JS in order to set group members.

**Thanks:**  
  This blueprint is a reworking of the excellent blueprint by [kpine] (https://gist.github.com/kpine)
