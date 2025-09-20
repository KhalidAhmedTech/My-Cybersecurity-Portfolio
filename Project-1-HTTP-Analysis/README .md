 Project 1: Analyzing HTTP Traffic
Objective: To show a fundamental understanding of network communication and the risks of unencrypted protocols.
Scenario: A client browses a website using the insecure HTTP protocol.
Process:
Capture: Used Wireshark to capture network traffic while browsing `http://example.com`.
Filtering:Applied the filter `http` to isolate the web traffic.
Analysis: Inspected the captured packets to identify key details in the HTTP GET request, such as the Host(`example.com`) and the User-Agent (identifying the web browser). I also examined the HTTP 200 OK response to find the `Content-Type`.
Outcome: I successfully demonstrated how to decode HTTP packets, showing a clear understanding of the request-response cycle and the type of data being exchanged.