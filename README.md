1. Understanding Snort
We explored Snort, an open-source Intrusion Detection System (IDS) and Intrusion Prevention System (IPS).
It allowed us to analyze network traffic in real-time, detect suspicious activities, and take action based on predefined rules and signatures.

3. Installing & Setting Up Snort
We successfully installed Snort and configured it by:

Setting up snort.conf to define our network.
Enabling logging and output settings to capture traffic.
Verifying the installation by running Snort in test mode.
3. Running Snort in Different Modes
To understand its capabilities, we ran Snort in multiple modes:

Sniffer Mode: Captured and displayed live network packets.
Packet Logger Mode: Logged packets for deeper analysis.
NIDS Mode: Used predefined and custom rules to detect threats and generate alerts.
4. Writing & Testing Snort Rules
We wrote and tested various Snort rules, including:

Basic Rules: Detected specific IP traffic.
Content-Based Rules: Looked for keywords or payload signatures.
Flow-Based Rules: Monitored session-based behaviors.
Threshold Rules: Reduced alert fatigue by limiting repeated detections.

We applied Snort in a real-world scenario by:

Monitoring live network traffic to detect unauthorized access attempts.
Logging and analyzing alerts to understand potential threats.
Testing Snort’s ability to recognize port scans, brute-force attempts, and malicious payloads.
6. Understanding Snort’s Non-Penetrative Traits
We noted that Snort operates as a passive monitoring tool unless configured as an IPS. This means:

It detects and alerts on threats without modifying network traffic.
It relies on rule-based detection, not active exploitation.
It enhances network visibility without causing disruptions.
7. Strengthening Our Information Security Knowledge
Working with Snort reinforced key security principles, including:

The importance of continuous network monitoring.
Recognizing common threats like DDoS, port scanning, and malware traffic.
The need to regularly update rulesets to detect emerging threats.
Implementing Snort alongside firewalls, SIEM, and endpoint security for a layered defense strategy.
