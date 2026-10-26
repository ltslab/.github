# ltslab

Community long-term support builds for the Spring Boot 3.5.x dependency stack.

Everything lives in one repository: **[ltslab/spring-lts](https://github.com/ltslab/spring-lts)**.
It holds the plan, the security patch series, and, as they are added, the CVE data, the BOM, and
the release automation.

> **Status: bootstrap. Nothing has been published.** There is no Maven Central artifact yet.

- Fixes are backported from public upstream commits only, each with a test that fails before
  the fix and passes after it.
- Artifacts will be published under `io.github.ltslab` with upstream artifact IDs.
- To report a vulnerability, see [SECURITY.md](https://github.com/ltslab/.github/blob/main/SECURITY.md).
  Do not open a public issue.

ltslab is an independent, non-commercial community project. It is not affiliated with,
endorsed by, or supported by Broadcom or the Spring team. "Spring" and related marks are
trademarks of Broadcom and are used only descriptively.
