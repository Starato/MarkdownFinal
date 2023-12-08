# **Transport Layer**

Summary: Transmits data using transmission protocols including TCP & UDP

The transport layer takes data from the session layer and deconstructs it into "segments" on the transmitting side. It is responsible for reassembling the segment on the receiving end. It turns it back into data that can be used by the session layer. The transport layer also carries out flow control, sending data at a rate that matches the connection speed of the receiving device. During all this there is also error control, checking if data was received correctly and if not, requesting it again.

![Transport Layer](https://images.ctfassets.net/aoyx73g9h2pg/1dEg4tNJPhu0lFIr12j9TC/872ed4cfec663ad036ec1b8e13d1f05a/Transport-Layer-Protocols-Diagram.jpg)
