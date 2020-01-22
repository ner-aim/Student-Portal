# Smart ID card using NODEMCU and RFID on WEB interface

A Smart College ID card is a RFID tag detected by a RFID reader. The user needs to
hover his card over the reader to log in and thereover has to enter a password into a
portal. A radio frequency identification reader (RFID reader) is a device used to gather
information from an RFID tag, which is used to track individual objects.
Radio waves are used to transfer data from the tag to a reader. 

The RFID reader is connected to the server through NodeMCU which will return USER ID to the log in
page. Through the portal, the user can access various features provided to him.
For the secure log-in into the portal, a cryptography algorithm is applied in the database.
The user ID is stored and sent in a encrypted pattern which makes the attacker Oscar to
decrypt it with patience. Also to enter the portal, the attacker should be dangling with
the user’s phone/registered number for the OTP in order to log-in to the portal.
