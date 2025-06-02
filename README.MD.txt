
🔹 1. Install Wireshark
Download from: https://www.wireshark.org/download.html

Install it on your computer like any other software.

🔹 2. Start Capturing Network Traffic
Here's how to do it:
Open Wireshark.

You'll see a list of network interfaces (Wi-Fi, Ethernet, etc.).

Click on the active one (usually Wi-Fi if you're on a laptop).

Wireshark will now start capturing live traffic!
I USE MY ETHERNET

🔹 3. Generate Some Traffic
To capture meaningful data:

Open a browser and visit 2-3 websites like:
https://example.com, https://wikipedia.org

Or open CMD/Terminal and run:

nginx
Copy
Edit
ping google.com
Do this for about 1 minute.

🔹 4. Stop the Capture
In Wireshark, click the red square button to stop the capture.

Now you’ll see lots of data (packets) captured.

🔹 5. Filter by Protocol
Let’s make things clear by filtering the view:

In the filter bar at the top, type protocols like:

http → shows only HTTP packets

dns → shows only DNS packets

tcp → shows TCP packets

udp → shows UDP packets


🔹 6. Identify at Least 3 Protocols
Look for and note these protocols:

DNS – used to look up website names (like google.com)

HTTP/HTTPS – website traffic

TCP/UDP – how data is sent

ICMP – used for ping

🔹 7. Export the Capture
Now save your work:

Go to File > Export Specified Packets

Save it as KUNAL_task5.pcap

🔹 8. Write a Short Report

Wireshark Traffic Analysis Report – Task 5

Date: [02/06/25]
Tool Used: Wireshark
Duration of Capture: 1 minute

Protocols Identified:

DNS – Used to resolve domain names.

HTTP – For browsing websites.

TCP – Transmission protocol for web traffic.

Interesting Observations:

Saw several DNS queries when visiting websites.

HTTP requests show which pages I accessed.

TCP established connections with servers.

Conclusion:
This task helped me understand how protocols work when I browse the internet, and how Wireshark can be used to troubleshoot or study network behavior.

