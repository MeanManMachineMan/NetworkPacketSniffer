# NetworkPacketSniffer
A custom built network packet sniffer to emulate some features of the popular application Wireshark, written using Java swings in Netbeans. Maven, the build automation tool mainly used for Java projects was used in order to package all the code,images and dependencies into a single executable JAR file which enables portability from device to device.

Below are the screenshots of my application. 

1. This window shows the available network interfaces.

![Available Network Interfaces](https://i.imgur.com/1pevyF5.png)

2. Upon choosing the interface, the user can then capture the packets in promiscuous mode.

![Capture packets](https://i.imgur.com/lAzZOrO.png)

3. A more detailed view of the packets follows.

![Detailed view](https://i.imgur.com/7Xg3B3Y.png)

![Headers](https://i.imgur.com/589ehOE.png)

![Raw data](https://i.imgur.com/zIRJRWR.png)

![Length](https://i.imgur.com/Fs9zAdk.png)

![Payload](https://i.imgur.com/fivV4Qi.png)

![Stats](https://i.imgur.com/5GGonVo.png)

4. Packets can be saved to the device and viewed using existing softwares like Wireshark or TCPDump.

![Dump packets](https://i.imgur.com/x0yQqYN.png)

The JAR file can be run through cmd using 
```
java -jar check-1.0-SNAPSHOT-shaded.jar
```

In order to run the application successfully, one must have the following installed:
1. [Npcap](https://nmap.org/npcap/windows-10.html)
2. [Pcap4J](https://github.com/kaitoy/pcap4j)

If you need to use any code snippet in your own projects, please contact me for permission and give due credit(vidur.p11@gmail.com)! ;)

Once installed successfully, the application should run flawlessly. Enjoy!
