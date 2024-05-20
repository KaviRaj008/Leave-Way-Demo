OVERVIEW:
This project proposes a mobile application for Android Auto  designed to streamlining emergency response by alerting drivers 300 meters ahead of an approaching emergency vehicle. Traditional emergency vehicle sirens can be obstructed by traffic noise or limited visibility, leading to delays in driver reaction and hindering smooth passage. To address this issue, this App leverages real-time location sharing using socket.io, predictive path analysis, and targeted alerts to notify drivers in advance about  the presence of emergency vehicle

WORKING DEMO:
https://kaviraj008.github.io/Leave-Way-Demo/

WORKING:

1, Client-side: The Android Auto app we develop will include a JavaScript client library for Socket.io. This library will establish a connection to our server.

2, Server-side: Our Node.js server will have a corresponding Socket.io server library. This library will handle incoming connections from clients, manage communication channels (sockets), and facilitate data exchange.

3, Event-driven communication: Both server and client can emit events and listen for events emitted by the other party. This allows for real-time updates. For example, the server can emit an event when an emergency vehicle enters the designated radius around a user's car. The client can listen for this event and trigger an alert within the app.
4, Geolocation API: These APIs  are essential for obtaining the real-time location of the user's passenger vehicle. This information is crucial for determining the user's position relative to approaching emergency vehicles

5, MongoDB: MongoDB, a NoSQL database, is well-suited for storing non-relational data like emergency vehicle location information. This could include emergency vehicle type, location coordinates, user, user location and timestamps if such data is available from a reliable and authorized source
6, Algorithm: Algorithm is used to calculate if the emergency vehicle is 300 meters behind the user, then alert the user.  

ADVANTAGES OF OUR APP:

1, Improved Driver Awareness: Timely in-vehicle alerts significantly enhance driver awareness of approaching emergency vehicles, compared to solely relying on sirens and lights.
2, Faster Response Times: Quicker driver response translates to faster response times for emergency vehicles, improving their effectiveness and potentially saving lives.
3, Reduced Traffic Congestion: By facilitating faster response times, the app can help minimize traffic congestion caused by delayed emergency vehicle movement.
4, Non-intrusive Alerts: The app prioritizes clear but non-distracting alerts to minimize driver distraction compared to loud sirens.

CONTRIBUTORS :
1, KAVI RAJ - BACKEND https://github.com/KaviRaj008/
2, JOHIN GILL - FRONTEND https://github.com/jooxlearner
3, PRATHIPA - FRONTEND 

NOTE: contribution from others are welcome  


