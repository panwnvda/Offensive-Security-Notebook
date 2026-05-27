# Introduction

I'm Wencheng Xue — 18 years old and a freshman at the University of Cincinnati. I picked up OSCE3 at 17, which combines OSWE, OSEP, and OSED — OffSec's triple-expert track covering web application exploitation, evasion-aware penetration testing, and Windows user-mode exploit development. I spend most of my time on offensive security work: red team operations, Active Directory attack tradecraft, web application security, and binary exploitation. CTFs and continuous certification study fill the rest of the time.

This notebook is the running reference I built while going through certification curricula and engagement work. The goal was to keep every technique I've actually used in one place, with the code ready to run after substituting a few values for the target environment. The content draws from six certifications: CPTS and CAPE from Hack The Box, OSCP and OSEP from OffSec, CRTP from Altered Security, and CRTO from Zero-Point Security. CPTS covers broad penetration testing methodology, CAPE goes deep on Active Directory, OSCP teaches the foundations, OSEP adds evasion and stealth in AD environments, CRTP focuses on on-prem AD attack tradecraft, and CRTO covers the full operator workflow including C2 and evasion.

## Disclaimer

Everything documented here is for authorized security testing, defensive understanding, and educational purposes only. The techniques and code are meant to be used in engagements with explicit written authorization, in personal lab environments, in CTF challenges, or as part of academic and professional certification study. They are not meant for anything else.

Do not use any of this material against systems, networks, or people you are not explicitly authorized to test. Unauthorized access to computer systems is a crime in most jurisdictions. The author and the certification programs whose material is referenced assume no liability for misuse. When a section mentions an OPSEC consideration — only run in an authorized lab, coordinate with the engagement scope, do not exfiltrate other users' data — that is not advisory; that is the bar.

Original course material remains the intellectual property of its respective providers: Hack The Box, OffSec, Altered Security, and Zero-Point Security. The content here paraphrases technique-level tradecraft and does not reproduce verbatim course text.
