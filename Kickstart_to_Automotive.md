# Kickstart to Automotive Cybersecurity - Quiz & Answers 
Join the Community: [AutoSecurityy](https://nas.io/autosecurityy)
## Day 1
It was introductary day to the basics of automotive 
security.
- What is asset in context of automotive cybersecurity?
  - Object that has value, or contributes to value(system/data/component in the vehicle which needs to be protected)
- Can you tell us few cybersecurity risks to a modern vehicle?
  - Everything is okay related to automotive systems.
## Day 2
The day, we dove into the intricacies of the CAN bus and its security vulnerabilities.
- Full form of CAN?
  - Controller Area Network
- What is ECU in a vehicle?
  - Electronic control unit or Embedded system in car that control one or more functionalities.
- Which arbitration id does not have highest priority (0x13,0x123,0x7E8,0x111)?
  - 0x7E8
- How does a complete can frame look like?
  - 123#AABBCC00FFEE0000, including explaination of complete frame structure. 
- Can you differentiate the DoS(Zero-ID)attack and firehose attack?
  - In a DoS (Zero-ID) attack we flood the CAN network with 0x000 which indicates that the message that is being send has highest priority and should be send first where as in case of Firehouse attack, attacker sends a pool of messages flooding the network which prevents the system to send legitimate messages to the network.
## Day 3
We learned about common CAN bus attacks.
- Which tools can be used to capture and replay the can messages?
  - candump & canplayer but not limited to CAN libraries
- What is the expected result of a successful dos attack on the can bus?
  - It will disrupt normal CAN communication, leading to system instability, safety risks, and potential failure of critical vehicle functions.
- Why do vulnerabilties arise in can bus which features & lack of security controls?
  - It rise primarily due to lack of built-in security features, broadcast nature of CAN, priority-based arbitration, error handling mechanisms.
## Day 4
Explore Key Fob systems, a crucial component in modern automotive 
security.
- How do key fobs system enhance vehicle security and what are the primary components?
  - Encryption, rolling codes, challenge-response mechanisms, securefob, UWB, etc.
- Diferrence between fixed-code and rolling-code key fob systems?
  - In fixed code, static/same code will be transmitted. Where in rolling code it will have a set of rollling codes stored in it, and it will be transmit based on synchronization counter.
- Who found rolljam vulnerability?
  - Samy Kamkar
## Day 5  
Intro to telemetry in automotive systems.
- What types of data are typically collected through automotive telemetry system?
  - Various sensor data to enhance user experience and for real time monitoring, gps data, vehicle health status, etc will all flow through telematic unit.
- How does telemetry data flow from the vehicle to the cloud?
  - Data will be gathered via serial communications by TCU, then prepare for sending to the cloud via web/api. Data can be event, request, periodic, or error based also.
- How can the lack of encryption in mqtt communication pose a security threat to connected vehicles?
  - Lack of encryption like SSL/TLS on MQTT will lead to mitm attacks which can be easily intercepted by an attacker to get brokers/domain, topics & msgs and manipulate the data.
- What was the last application vulnerability you discovered, and how could this type of vulnerability impact a vehicle's systems if it were present in an automotive environment?
  - some ans are just interesting!
## Day 6
Particpants gained a deeper understanding of the critical security controls deployed 
in automotive systems and their significance in mitigating cyber risks.
- No Quiz
## Day 7
Participants had a solid understanding of the future trends in automotive cybersecurity and be prepared to anticipate and 
respond to emerging challenges.
- No Quiz

