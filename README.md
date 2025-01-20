# Zenitel-Connect-Pro-Audio-Event-Detector
This solution integrates a Zenitel Connect Pro with Intellivision Audio Event Detector running as a Node-red flow. Integration implements listening to live events for threats such as gunshots, glass break and fire alarm. By using Node-red it's possible to add certain actions after the event is detected. This flow is used to issue a warning message which is stored on ZCP server, and place a call to operator after the event is detected and warning message is played.
To test this flow, follow next steps : 
1. Ensure that Intellivison Audio Event Detector is up and running.
2. Ensure the licence for Audio Event Detector is valid.
3. Ensure the flow is deployed on Zenitel Connect Pro server, port 1880.
4. Ensure that nodes contain valid credentials and configuration.
5. Ensure that nodes contain valid directory numbers for playing warning messages.
6. Ensure that nodes contain valid directory numbers for establishing calls to the operator.
7. Use sample sound to simulate gunshot, glass break or fire alarm.
8. Gauges in Node-red dashboard should move when the event is detected.
9. Warning message should be played when the event is detected.
10. Call should be placed to the operator after the messsage is played.
11. Events are logged in Node-red dashboard.

