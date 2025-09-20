Project 2: Unencrypted Password Discovery
Objective
To demonstrate the ability to identify vulnerabilities in outdated protocols and to emphasize the importance of encryption in protecting sensitive information like passwords.

Scenario
I logged into an insecure website (HTTP) to analyze the traffic being transmitted.

Methodology
Packet Capture: I used Wireshark to capture network traffic during the login attempt on the website.

Filtering and Analysis: I applied the filter http.request.method == "POST" to isolate the specific packet related to the login process.

Content Inspection: I analyzed the packet and expanded the HTML Form URL Encoded section, where the login credentials (username and password) were clearly visible.

Conclusion
This project proved that unencrypted protocols transmit sensitive information as plain text, making it vulnerable to interception. This highlights the critical importance of using HTTPS on all websites that handle personal or sensitive data.