# Wireshark for Basic Network Security Analysis 
<br />
<h2>Description</h2> 
Here we will learn how to capture & locate a packet and create our own network traffic. In the end you will able to investigate the source, destination of the packets, protocols used and the basic step by steps for network security analysis.
<h2>Radius Packet</h2> 

<p align="center">
  <br />
<img src= "https://i.imgur.com/LEa0kZW.png[/img]" alt="radius pcap in wireshark"/>
 <br />
  
Here I have the Wireshark program running and located the file Radius.pcap under the DESKTOP icon to analyze network traffic. 
 <br />
 
  <h2>Network Traffic Analysis</h2>
Here is all traffic that has been captured before and stored. You can analyze the time, investigate the source, and destination adresses of the packets. You can check to see the protocol used and any other information needeD byc clicking each line to open information inside the packets.
  <br />
  
<p align="center">
  <br />
<img src= "https://i.imgur.com/miB0I0S.png[/img]" alt="Network traffic capture analysis"/>
 <br />
  
 <h2>Packet Capture</h2> 
To capture a packet we locate the network interface that is connected to this machine by clicking FILE then the CLOSE button. Here we have located Ethernet 3 below. 
  
  <br />
  <p align="center">
  <br />
<img src= "https://i.imgur.com/gq4Rd3X.png[/img]" alt="ethernet3 machine"/>
 
    <br />
After double-clicking Ethernet 3, you will see all of the traffic appear.
  <br />
    
  <p align="center">
  <br />
<img src= "https://i.imgur.com/Ix0hoDi.png[/img]" alt="e3 traffic"/>
 <br />
    
You can filter the traffic to only show certain protcols. Here I've filtered traffic based on the DNS protocol.

<br />
     <p align="center">
  <br />
<img src= "https://i.imgur.com/px9xuLY.png[/img]" alt="dns traffic"/>
 <br />
 
       Note: If the bar appears green that means the filer exists, if not the bar appears red.
<br />

<h2>Generating DNS traffic</h2> 
<br />
If no DNS traffic appears you can generate it. Click the windows icon and type in 'command prompt' to locate command prompt.
 <br />
 
  <p align="center">
  <br />
<img src= "https://i.imgur.com/EDohsSp.png[/img]" alt="command prompt"/>
 <br />
Type ping then any site of your choosing. Here I typed in www.coursera.com. As you can see the ping starts to generate.
 <br />
 
  <p align="center">
  <br />
<img src= "https://i.imgur.com/GHjGSuC.png[/img]" alt="coursera in command prompt"/>
 <br />
Next you will click ctrl (control) plus the letter C to stop the ping. 
 <br />
 
  <p align="center">
  <br />
<img src= "https://i.imgur.com/04BTbXb.png[/img]" alt="control c in command prompt"/>
 <br />
As you can see a dns server with the name of www.coursera.com appears in your network traffic.
     <br />
 
  <p align="center">
  <br />
<img src= "https://i.imgur.com/zHp5yfZ.png[/img]" alt="dns server appears"/>
 <br />
Click the red square button on the left hand side to stop the traffic of that dns server. 
 <br />
 
  <p align="center">
  <br />
<img src= "" alt=""/>
 <br />
    
Click file and close and delete the filter.
 <p align="center">
  <br />
<img src= "https://i.imgur.com/udbpx7R.png[/img]" alt="dns server and file close"/>
 <br /


    Summary: Now we can work with Wireshark and it's basic tools. You can view captured packets and also capture traffic

