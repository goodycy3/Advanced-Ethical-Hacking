# Advanced Ethical Hacking Report
This is an Advanced Ethical Hacking Report prepared as part of a course assessment for my MSc program.

<img width="1004" alt="image" src="https://github.com/user-attachments/assets/bb092adb-69cf-4d6e-a570-ba80db1d2b85" />


# Summary of Report Executive Summary
The penetration testing report outlines a detailed assessment of the Websploit infrastructure, identifying vulnerabilities, assessing risks, and proposing actionable mitigations. The primary objective was to evaluate the security posture of containers within the DC31 environment, and to provide a roadmap for securing them against potential exploitation.
Key findings include:
- Redis Vulnerability (DC31_01): A critical remote code execution (RCE) vulnerability (CVE-2022-0543) was discovered in the Redis service, exposing the system to unauthorized code execution risks.
- Apache Druid Vulnerability (DC31_02): An input validation issue (CVE-2023-25194) in Apache Druid could allow attackers to execute arbitrary commands and compromise sensitive data.
- Openfire Vulnerability (DC31_03): A path traversal flaw (CVE-2023-32315) in Openfire enabled attackers to create unauthorized admin accounts, upload malicious plugins, and potentially escalate privileges.

The penetration test also highlighted areas requiring immediate attention, including inadequate network segmentation, misconfigured services, and missing updates. By addressing these vulnerabilities, the organization can mitigate the risk of unauthorized access, data breaches, and system compromise.
Key Recommendations:
- Patch identified vulnerabilities by updating Redis, Apache Druid, and Openfire to their latest secure versions.
- Strengthen access controls, including limiting IP-based access to critical services.
- Implement monitoring and logging solutions to detect and respond to unauthorized activities in real-time.
- Conduct regular vulnerability scans and penetration tests to maintain a robust security posture.
