IT Help Desk Ticketing System

 Project Overview

This project demonstrates practical IT Help Desk workflows using Jira Service Management. It covers support ticket creation, incident investigation, diagnostic documentation, and ticket management.

The project uses a simulated user support request involving a Windows 11 Wi-Fi connectivity problem.

Objectives

- Create and manage IT support tickets in Jira Service Management.
- Record incident details and troubleshooting notes.
- Perform basic Windows network diagnostics.
- Document findings and potential causes.
- Practise ticket prioritisation and status tracking.
- Maintain professional technical documentation.

 Tools and Technologies

- Jira Service Management
- Windows 11
- Command Prompt
- `ipconfig`
- `ping`
- `nslookup`
- GitHub and Markdown

Project Scenario

Ticket title: User unable to connect to Wi-Fi

Issue category: Network connectivity

Priority:High, as configured in the practice ticket

Environment: Windows 11

Purpose: Investigate a reported Wi-Fi connectivity issue and document the diagnostic evidence before deciding on a resolution.

 Investigation Performed

| Test | Result | Interpretation |
|---|---|---|
| `ipconfig` | Private IPv4 address assigned | A private IPv4 address is configured |
| `ping 127.0.0.1` | Successful | The local TCP/IP stack responds |
| Default gateway ping | Successful | The gateway responds to the PC |

 Current Findings

The initial network checks were successful. The computer had a private IPv4 address, the localhost test succeeded, and the default gateway was reachable.

These results confirm basic local network functionality but do not establish that internet access and DNS resolution are working.

 Diagnosis

The root cause has not yet been confirmed. Additional internet connectivity, DNS, and browser tests are required.

Resolution

Pending further investigation and verification. No network configuration changes have been made as part of the documented initial checks.

 Ticket Workflow

1. Create a support ticket.
2. Record the reported issue.
3. Perform initial diagnostic checks.
4. Document findings in Jira.
5. Continue investigating based on the evidence.
6. Apply a suitable fix if required.
7. Verify the outcome before resolving the ticket.



 Skills Demonstrated

- IT service desk ticket handling
- Windows network troubleshooting
- Basic TCP/IP diagnostics
- Incident documentation
- Technical communication
- GitHub project documentation

 Disclaimer

This is a learning project using a simulated support incident. Diagnostic results are documented from the checks performed. No claim of resolution is made until the issue has been investigated and the outcome verified.
