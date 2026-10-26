# Security policy

This policy applies to every repository in the `ltslab` organization.

## Reporting a vulnerability

Report privately through GitHub:
<https://github.com/ltslab/spring-lts/security/advisories/new>.

Do not open a public issue, pull request, or discussion for a suspected vulnerability.

Include the affected component and version, a description of the issue, and steps or a test
that reproduce it. If the issue is in upstream Spring or Reactor code, report it to the upstream
project as well; ltslab backports public upstream fixes and does not develop independent fixes
for undisclosed upstream vulnerabilities.

## What is in scope

- The patch series, build, and release tooling in `ltslab/spring-lts`.
- Artifacts published under `io.github.ltslab`, once they exist.

## Supported versions

Nothing has been published yet. Once the first release train exists, the supported versions
will be listed in `ltslab/spring-lts`.

## Response

ltslab is a volunteer, non-commercial project. Reports are handled on a best-effort basis; there
is no contractual response time.
