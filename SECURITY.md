# Security

Tenable takes the security of our software and services seriously, which includes all source code repositories managed through our GitHub organization.


If you believe you have found a security vulnerability in any Tenable repository, please report it to us as described below.

## Reporting Security Issues

**Please do not report security vulnerabilities through public GitHub issues.**

To help ensure that we have enough information to properly evaluate a potential issue, Tenable asks that you email us at <vulnreport@tenable.com> and please include the following in your report:

- A description of the issue explaining the vulnerability, including the impact to the user(s) or system. This should clearly describe how the issue crosses privilege boundaries.
- The affected product or resource (e.g., Tenable.io, Nessus, SecurityCenter, LCE, PVS, GitHub Repository), the software version, and the platform you are using (e.g., Windows 10, Debian Linux).
- A proof-of-concept or functional exploit that demonstrates the issue. If a proof-of-concept is not available, please include any relevant logs generated from your testing.
- Any caveats or conditions required to exploit the issue. Indicate if there are any non-default system settings, custom configurations, required user interaction, or anything else that would limit the attack.
- Any vulnerability database identifier you have requested. If you have not requested a CVE identifier, indicate if you would like us to request one.


Please note, potential vulnerabilities that do not by themselves expose a service or application to attack, are not considered valid issues. For example, injecting or the lack of an HTML tag does not necessarily mean an application is vulnerable to cross-site scripting, and injecting a single backtick (`) does not necessarily mean it is vulnerable to SQL injection.


Once we receive your report, Tenable will stay in touch with you to provide updates on our investigation and status of a fix for verified issues. During this time we might also request additional information. If the issue you reported is determined to be valid and affects one of our products, an advisory will be published when a solution is available for our customers.


Please indicate if and how you would like to be credited in the advisory (name, company or affiliation, etc). Tenable does not participate in a public bug bounty program or provide financial awards for finding issues.