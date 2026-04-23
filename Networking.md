HTTP - (Web browsing) TCP Connection -the initial communication (are you available) HTTP REQ HTTP RES

HTTP/3 - (Header Compression, Faster, Improved Performance, Better network Congestion) (IOT) (QUIC) UDP connection is established

HTTPS - (Web browsing) TCP Connection public key session key encrypted data

WebSocket - once http connection is done it upgrades to web socket (for live chat) HTTP Upgrade Full Duplex

TCP - ensures no packet is dropped while communication. we can consider this as path This happens in 3 stages SYN - are you available SYN+ACK ACK

UDP - doesn't guarantee package transfer (it may get drop). Its fast. Req Res

SMTP - (email) sender ->SMTP Server -> receiver

FTP - (uploading docs) Control Channel Data Channel





HTTP (HyperText Transfer Protocol) HTTP is a protocol for fetching resources such as HTML documents. It is the foundation of any data exchange on the Web and it is a client-server protocol.
HTTP/3 HTTP/3 is the next major revision of the HTTP. It runs on QUIC, a new transport protocol designed for mobile-heavy internet usage. It relies on UDP instead of TCP, which enables faster web page responsiveness. VR applications demand more bandwidth to render intricate details of a virtual scene and will likely benefit from migrating to HTTP/3 powered by QUIC. 3.HTTPS (HyperText Transfer Protocol Secure) HTTPS extends HTTP and uses encryption for secure communications.
WebSocket WebSocket is a protocol that provides full-duplex communications over TCP. Clients establish WebSockets to receive real-time updates from the back-end services. Unlike REST, which always “pulls” data, WebSocket enables data to be “pushed”. Applications, like online gaming, stock trading, and messaging apps leverage WebSocket for real-time communication.
TCP (Transmission Control Protocol) TCP is is designed to send packets across the internet and ensure the successful delivery of data and messages over networks. Many application-layer protocols build on top of TCP.
UDP (User Datagram Protocol) UDP sends packets directly to a target computer, without establishing a connection first. UDP is commonly used in time-sensitive communications where occasionally dropping packets is better than waiting. Voice and video traffic are often sent using this protocol. 7.SMTP (Simple Mail Transfer Protocol) SMTP is a standard protocol to transfer electronic mail from one user to another. 8.FTP (File Transfer Protocol) FTP is used to transfer computer files between client and server. It has separate connections for the control channel and data channel. Reference:https://medium.com/must-know-computer-science/system-design-client-server-communication-674818ca448d
Rest APIs Overview HTTP Req/Res with Headers HTTP Methods HTTP Status Codes Best Practices + Examples
