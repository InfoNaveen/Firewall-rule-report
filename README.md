# Firewall-rule-report

# Firewall Configuration Report

## Objective
[span_0](start_span)The objective of this task was to configure and test a basic firewall rule to allow or block network traffic on a Windows system.[span_0](end_span)

## Tools Used
* *[span_1](start_span)Tool:* Windows Defender Firewall with Advanced Security[span_1](end_span)

## Configuration Steps
A new inbound rule was configured to enhance system security. The following steps were taken:

1.  *Opened Advanced Security Panel:* Accessed the Windows Defender Firewall with Advanced Security management console.
2.  *Initiated New Rule:* Selected "Inbound Rules" and created a "New Rule...".
3.  *Configured Rule:* The rule was configured to block traffic for a specific port.
    * *Protocol:* TCP
    * *[span_2](start_span)Port:* 23 (Telnet)[span_2](end_span)
    * *Action:* Block the connection
4.  *Named and Saved:* The rule was named "Block Telnet Port 23 Task" and saved, activating it immediately.

## Summary of How a Firewall Filters Traffic
[span_3](start_span)A firewall acts as a security barrier between a trusted internal network and an untrusted external network (like the internet).[span_3](end_span) [span_4](start_span)It monitors and filters incoming and outgoing network traffic based on a predefined set of security rules.[span_4](end_span) [span_5](start_span)By allowing or blocking specific types of traffic to certain ports, it helps prevent unauthorized access and protect the system from cyber threats.[span_5](end_span)
## Deliverable: Firewall Rule Screenshot
[span_6](start_span)Below is the screenshot showing the newly created and enabled firewall rule in the Windows Defender Firewall console.[span_6](end_span)

![Firewall Rule Screenshot](firewallreport.png)
