- Recommended Model : Websocket
- Pub-Sub Messaging Queue : API Server will publish to the Message Queue and will subscribe to the data from the user. New message gets added to the queue
- Taking into consideration CAP theorem, we need more availability.
- NoSQL db like Cassandra or HBase will be more suitable for this system
- Media files are stored in Object Storage like AWS S3 and access can be further sped up by a CDN
![fb messanger](https://github.com/SteffiKeranJ/System-Design-Architecture/blob/main/facebook-messenger/Capture.PNG)
