# CVEs

This repository contains security vulnerabilities I have discovered, including details on affected products, impact, PoCs, and mitigation steps, following responsible disclosure practices.

# Security Vulnerabilities Discovered by Pablo Salinas

| CVE ID | Product | Version | Type | Vulnerable File | Affected Parameter | Impact | CVSS Score | Recommended Mitigation |
|--------|---------|---------|------|------------------|---------------------|--------|-------------|--------------------------|
| [CVE-2024-53438](https://nvd.nist.gov/vuln/detail/CVE-2024-53438) | ChurchCRM | 5.7.0 | SQL Injection | `EventAttendance.php` | `Event` | Allows arbitrary SQL command execution | **CVSS:3.1/AV:N/AC:L/PR:N/UI:N/S:U/C:H/I:H/A:H**<br>**9.8 - CRITICAL** | Use prepared statements and parameterized queries |
| [CVE-2025-26211](https://nvd.nist.gov/vuln/detail/CVE-2025-26211) | GibbonEdu | 29.0.00 | CSRF | `/modules/Timetable Admin/tt_delete.php` | `isActionAccessible` | CSRF vulnerability in versions prior to 29.0.00 | **CVSS:3.1/AV:N/AC:H/PR:N/UI:N/S:U/C:N/I:L/A:N**<br>**3.7 - LOW** | Implement anti-CSRF protections such as per-session tokens and verify the origin of incoming requests |

