# manop55555

maybe 0 or 1

## Tools & Languages

[![Skills](https://skillicons.dev/icons?i=bash,c,cpp,go,git,linux,lua,perl,python,ruby,rust,vim,vscode&theme=dark)](https://skillicons.dev)

![ARM Assembly](https://img.shields.io/badge/ARM_Assembly-A0522D?style=flat-square&logoColor=white)
![Binary Ninja](https://img.shields.io/badge/Binary_Ninja-4B0082?style=flat-square&logoColor=white)
![checksec](https://img.shields.io/badge/checksec-444444?style=flat-square&logoColor=white)
![GDB](https://img.shields.io/badge/GDB-333333?style=flat-square&logoColor=white)
![GDB-PEDA](https://img.shields.io/badge/GDB--PEDA-555555?style=flat-square&logoColor=white)
![Ghidra](https://img.shields.io/badge/Ghidra-FF0000?style=flat-square&logoColor=white)
![IDA Pro](https://img.shields.io/badge/IDA_Pro-004B8D?style=flat-square&logoColor=white)
![ltrace](https://img.shields.io/badge/ltrace-555555?style=flat-square&logoColor=white)
![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=flat-square&logoColor=white)
![NASM](https://img.shields.io/badge/NASM-333333?style=flat-square&logoColor=white)
![objdump](https://img.shields.io/badge/objdump-333333?style=flat-square&logoColor=white)
![one_gadget](https://img.shields.io/badge/one__gadget-FF4500?style=flat-square&logoColor=white)
![pwndbg](https://img.shields.io/badge/pwndbg-FF6600?style=flat-square&logoColor=white)
![pwntools](https://img.shields.io/badge/pwntools-4B0082?style=flat-square&logoColor=white)
![Radare2](https://img.shields.io/badge/Radare2-1A1A1A?style=flat-square&logoColor=white)
![readelf](https://img.shields.io/badge/readelf-222222?style=flat-square&logoColor=white)
![ROPgadget](https://img.shields.io/badge/ROPgadget-8B0000?style=flat-square&logoColor=white)
![Ropper](https://img.shields.io/badge/Ropper-CC0000?style=flat-square&logoColor=white)
![strace](https://img.shields.io/badge/strace-666666?style=flat-square&logoColor=white)
![strings](https://img.shields.io/badge/strings-555555?style=flat-square&logoColor=white)
![x86 Assembly](https://img.shields.io/badge/x86_Assembly-6E4C13?style=flat-square&logoColor=white)
![x86-64 Assembly](https://img.shields.io/badge/x86--64_Assembly-8B4513?style=flat-square&logoColor=white)

## CVE Disclosures

| CVE ID | Advisory | Severity | Type | Description |
|--------|----------|----------|------|-------------|
| CVE-2026-47667 | [GHSA-rmfc-grgj-qwhv](https://github.com/GreycLab/CImg/security/advisories/GHSA-rmfc-grgj-qwhv) | ![High](https://img.shields.io/badge/CVSS_7.5-High-red) | ![DoS](https://img.shields.io/badge/DoS_/_Memory_Leak-orange) | Uncontrolled Memory Allocation and Memory Leak in `_load_analyze()` in CImg (<= 3.7.6) via a crafted NIfTI/Analyze header — a file as small as 6 bytes can trigger an allocation of approximately 1.3 GB per call, with the full allocation leaked on every error path ([Issue #480](https://github.com/GreycLab/CImg/issues/480)) |
| CVE-2026-9104 | [GHSA-xxx9-hfqp-f83f](https://github.com/dartiss/draft-list/security/advisories/GHSA-xxx9-hfqp-f83f) | ![Moderate](https://img.shields.io/badge/CVSS_6.5-Moderate-orange) | ![Stored XSS](https://img.shields.io/badge/Stored_XSS-red) | WordPress Plugin Draft List (<= 2.6.3) — Contributor Stored XSS via Draft Title in Custom Drafts Template Attributes, using a quote-only payload to break out of an HTML attribute |
| CVE-2026-48093 | [GHSA-7c9x-px5v-5hcp](https://github.com/dartiss/code-embed/security/advisories/GHSA-7c9x-px5v-5hcp) | ![Moderate](https://img.shields.io/badge/CVSS_6.5-Moderate-orange) | ![Stored XSS](https://img.shields.io/badge/Stored_XSS-red) | WordPress Plugin Code Embed (<= 2.6) — Contributor Stored XSS via Remote URL Embed; the plugin fetches an external URL and inserts the response body into the page without sanitization |
| CVE-2025-10181 | [GHSA-jf7w-cp2r-c3jh](https://github.com/dartiss/draft-list/security/advisories/GHSA-jf7w-cp2r-c3jh) | ![Moderate](https://img.shields.io/badge/CVSS_6.4-Moderate-orange) | ![Stored XSS](https://img.shields.io/badge/Stored_XSS-red) | WordPress Plugin Draft List (<= 2.6) — Authenticated (Contributor+) Stored XSS via the `drafts` shortcode due to insufficient input sanitization and output escaping on user-supplied attributes |
| CVE-2026-48735 | [GHSA-wjqc-6w8f-h24c](https://github.com/py-pdf/pypdf/security/advisories/GHSA-wjqc-6w8f-h24c) | ![Moderate](https://img.shields.io/badge/Moderate-orange) | ![DoS](https://img.shields.io/badge/DoS_/_RAM_Exhaustion-orange) | pypdf (< 6.12.1) — Manipulated XMP metadata streams can exhaust RAM; an attacker can craft a PDF with large XMP metadata to cause excessive memory usage |
