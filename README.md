# Log-Parser
Microsoft Event Logs Analyzer

This tool is designed to analyze, sort, and organize logs based on time. Currently, it focuses on parsing Remote Desktop Protocol (RDP) connection logs. By using this tool, you can gain insights into the connections made to your device via RDP, including the connecting IP and the IP address of your device.

Additionally, the tool helps in identifying potential brute force attacks through the analysis of RDP logs.

## ‼️  Important Notes:

1. **Log Extraction:**
   - Before using the tool, please ensure that you extract your logs and create a copy in a separate directory. The tool requires its own set of logs for processing, as the original log files may be in use by your system.

2. **SID Resolution:**
   - SID resolution is only guaranteed on the same device where the log parsing occurs. If you copy logs to another device for analysis, some SID resolution may not take place. While this doesn't significantly impact most operations, it's essential to be aware of this limitation.

## Under Processing:

The tool is currently undergoing development to integrate RDP logs with Sysmon logs by time. This enhancement will provide a more comprehensive understanding of system activities over time.

---
