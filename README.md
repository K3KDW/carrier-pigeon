# Carrier-PiGeon
WSPR as a one-way status communicator. Used in the field on a raspberry pi zero running Threeme3's fork of WsprryPi. Useful for communicating basic status and help messaged when there is no cell service, phones are dead, other parties don't have amateur radio licenses, APRS is not accessible, or larger two-way radios are not practical. 

## TL;DR - Two letters and two numbers are used to send messages instead of maidenhead grid locators. Status reports are accessed via the various WSPR reporter websites or mobile apps. Enter the sender's amateur radio callsign and look at their most recently reported grid locations to view status codes.

TODO:
1)  Add fields to indicate forthcoming grid locators to aid in sending location. This will require 6 character grid locators which I have not yet tested in     Wsprrypi.
2)  Add frequencies and lengths for making improvised dipoles.
