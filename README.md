# CVEs
This repository contains security vulnerabilities I have discovered, including details on affected products, impact, PoCs, and mitigation steps, following responsible disclosure practices.

# Security Vulnerabilities Discovered by Pablo Salinas  

| CVE ID         | Product    | Version | Type           | Vulnerable File      | Parameter Affected | Impact                                | CVSS Score                                      | Mitigation                                    |
|---------------|-----------|---------|---------------|----------------------|--------------------|----------------------------------------|------------------------------------------------|-----------------------------------------------|
| [CVE-2024-53438](https://nvd.nist.gov/vuln/detail/CVE-2024-53438) | ChurchCRM | 5.7.0   | SQL Injection | `EventAttendance.php` | `Event`            | Allows execution of arbitrary SQL commands | **CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H** 9.8 CRITICAL | Use prepared statements and parameterized queries |

