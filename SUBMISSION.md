## Tinkercad Circuit Link

```
https://www.tinkercad.com/things/3jyiOlSOwRh-shiny-sango-jaiks/editel?returnTo=https%3A%2F%2Fwww.tinkercad.com%2Fdashboard&sharecode=VoIwS__E-azDe-GAMT657l3E8Fz4gLWh0FeL_8Q2pds```

## Program Explanation
```
This is a Reaction time module from the technical assessment. I have the button, LCD and the LED in separated circuits. 
State: This tester is heavily modulised with states of the tester (Idle, Armed, Reaction, Result, fStart(false start), Start (when you're supposed to press the button). 
LED: This tester has the LED's behaviours in the void loop section (under the LED behaviours), there are Off, On, sPulse (slow pulse) and fPulse (fast pulse).
LCD: This reaction tester also uses LCD to inform the user about the results and the state of the tester (because LED alone can be confusing). It displays idle, armed, start, and results (reaction time, attempts, failed attempts, and best time with the panel updated every 2 second until it is back to idle).
I used enum to basically turn LED, and the states of the tester in order to automate the command later on and reduce the number of lines needed for the script, also creates a checkpoint for codes if they ended up wrong.
In order to make the script easier to understand I've labelled each section with //.
```
