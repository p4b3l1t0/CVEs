# CVEs
This repository contains security vulnerabilities I have discovered, including details on affected products, impact, PoCs, and mitigation steps, following responsible disclosure practices.

# Security Vulnerabilities Discovered by Pablo Gabriel Salinas  

| CVE ID         | Product    | Version | Type           | Vulnerable File      | Parameter Affected | Impact                                | Mitigation                                    |
|---------------|-----------|---------|---------------|----------------------|--------------------|----------------------------------------|-----------------------------------------------|
| [CVE-2024-53438](https://nvd.nist.gov/vuln/detail/CVE-2024-53438) | ChurchCRM | 5.7.0   | SQL Injection | `EventAttendance.php` | `Event`            | Allows execution of arbitrary SQL commands | Use prepared statements and parameterized queries |


