### Amir Aliu

I break things and build things. 16 CVEs across IoT devices and open-source CMS platforms.

| Target | CVEs | Findings | |
|---|---|---|---|
| Fullhan AJL30PG0803 IP camera | 6 | Unauthenticated OS command injection, exposed snapshots, default root Telnet, plaintext credential disclosure | [Read Writeup](https://amiraliu.vercel.app/blog/breaking-into-my-own-camera) |
| Camaleon CMS 2.9.1 | 7 | Authenticated RCE, SSTI-to-RCE, stored XSS, SQLi, broken access control. Co-discovered with [@enrik-m](https://github.com/enrik-m), credited in [v2.9.2](https://github.com/owen2345/camaleon-cms/releases/tag/2.9.2) | [Read Writeup](https://amiraliu.vercel.app/blog/camaleon-cms-cve) |
| MaxSite CMS | 3 | Auth bypass, unauthenticated RCE via PHP code injection and object injection | |

<details>
<summary>CVE IDs</summary>

**Fullhan:** [51402](https://nvd.nist.gov/vuln/detail/CVE-2026-51402), [51403](https://nvd.nist.gov/vuln/detail/CVE-2026-51403), [51404](https://nvd.nist.gov/vuln/detail/CVE-2026-51404), [51405](https://nvd.nist.gov/vuln/detail/CVE-2026-51405), [51406](https://nvd.nist.gov/vuln/detail/CVE-2026-51406), [51407](https://nvd.nist.gov/vuln/detail/CVE-2026-51407)

**Camaleon:** [66748](https://nvd.nist.gov/vuln/detail/CVE-2026-66748), [67616](https://nvd.nist.gov/vuln/detail/CVE-2026-67616), [73326](https://nvd.nist.gov/vuln/detail/CVE-2026-73326), [73329](https://nvd.nist.gov/vuln/detail/CVE-2026-73329), [73330](https://nvd.nist.gov/vuln/detail/CVE-2026-73330), [73331](https://nvd.nist.gov/vuln/detail/CVE-2026-73331), [73332](https://nvd.nist.gov/vuln/detail/CVE-2026-73332)

**MaxSite:** [70552](https://nvd.nist.gov/vuln/detail/CVE-2026-70552), [70553](https://nvd.nist.gov/vuln/detail/CVE-2026-70553), [70554](https://nvd.nist.gov/vuln/detail/CVE-2026-70554)

</details>

Building [Silent Hill 3 Enhanced](https://github.com/amiraliuks/silent-hill-3-enhanced), reverse-engineering and modernizing the original PC release.

More at [amiraliu.vercel.app](https://amiraliu.vercel.app)
