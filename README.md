👋 Hi, I’m Peter, also known as @p-. I'm a security researcher at the [GitHub Security Lab](https://securitylab.github.com/). I've started out as a software engineer and have first hands experience what it means to protect applications against threats and fix vulnerabilities.
I’m especially interested in vulnerabilities in implementations of authentication protocols and deserialization vulnerabilities. My main tool for querying and identifying vulnerabilities in source code is [CodeQL](https://codeql.github.com/).

Here are some **authentication related vulnerabilities** I've found:

* [CVE-2023-20900](https://support.broadcom.com/web/ecx/support-content-notification/-/external/content/SecurityAdvisories/0/23664) - SAML token signature bypass in VMware Tools
* [CVE-2022-39366](https://github.blog/2023-03-03-github-security-lab-audited-datahub-heres-what-they-found/) - Missing JWT signature check in DataHub
* [GHSL-2023-163 & GHSL-2023-164](https://github.blog/2023-11-30-securing-our-home-labs-home-assistant-code-review/) - Authorization Code Exfiltration & Unrestricted OAuth2 Clients in Home Assistant
* [CVE-2021-22160](https://www.openwall.com/lists/oss-security/2021/05/25/4) - Improper Verification of Cryptographic Signature in Apache Pulsar

Excerpt of some **vulnerabilities due to unsafe deserialization** I've found - covering 4 different programming languages (C#, Java, Ruby & Elixir):

* [CVE-2024-28213](https://github.com/advisories/GHSA-j7jm-8gf5-frcm) - nGrinder vulnerable to unsafe Java objects deserialization
* [CVE-2022-36038](https://securitylab.github.com/advisories/GHSL-2022-069_CircuitVerse/) - Remote Code Execution (RCE) in CircuitVerse
* [CVE-2020-15150](https://github.com/duffelhq/paginator/security/advisories/GHSA-w98m-2xqg-9cvj) - Paginator (for Elixir Ecto): Remote Code Execution Vulnerability
* [CVE-2018-8540](https://msrc.microsoft.com/update-guide/en-US/advisory/CVE-2018-8540) - Microsoft .NET Framework: Remote Code Injection Vulnerability


- Publications:
    - My posts on the [GitHub Blog](https://github.blog/author/stockli/)
    - 🗨️ Mastodon: [@ulldma](https://infosec.exchange/@ulldma)
    - 🗨️ Twitter/X: [@ulldma](https://twitter.com/ulldma)

