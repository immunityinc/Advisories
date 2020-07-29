# Advisories

## 2020

### CVE-2020-13172

**Title:** Origin Information Disclosure  
**Vendors contacted:** Electronic Arts Inc.  
**Release mode:** Coordinated Release  
**Credits:** This vulnerability was discovered by Andres Blanco.  
**Class:** Insertion of Sensitive Information Into Debugging Code [CWE-215]  
**Severity:** Medium - 5.5 (CVSS:3.1/AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:N/A:N 5.5)  
**Summary:** A Information Disclosure vulnerability is present within the ‘Origin.exe’ process, this kind of attack allows local malicious users to access sensitive user information.

[Full Report](2020/CVE-2020-13172.pdf)

### CVE-2020-15524

**Title:** Local Privilege Escalation in Origin  
**Vendors contacted:** Electronic Arts Inc.  
**Release mode:** Coordinated Release  
**Credits:** This vulnerability was discovered by Joel Noguera in collaboration with Lautaro Fain.  
**Class:** Uncontrolled Search Path Element [CWE-427]  
**Severity:** High - 7.8 (CVSS:3.1/AV:L/AC:L/PR:L/UI:N/S:U/C:H/I:H/A:H)  
**Summary:** A Local Privilege Escalation attack scenario is present within the ‘OriginClientService.exe’ process, this kind of attack allows malicious users to elevate privileges within the target system and therefore perform actions that otherwise they would not be able to execute. In this particular case, attackers will be able to escalate from a Windows Non-Privileged user to NT AUTHORITY/SYSTEM by planting a DLL in a Qt Path on which they have control.

[Full Report](2020/CVE-2020-15524.pdf)
