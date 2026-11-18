# Security policy

This policy applies to every repository of the GitHub organisation `ifdd-de`
that has no `SECURITY.md` of its own.

## Reporting a vulnerability

Please do not open a public issue. Report privately instead, in one of two
ways:

- GitHub's private vulnerability reporting: "Report a vulnerability" on the
  Security tab of the affected repository;
- an e-mail to `maintainers@ifdd.de`.

Please include the affected repository and version (tag or commit), the steps
to reproduce and the impact as you see it.

The maintainers work on IFDD in their own time. They confirm a report, keep
you informed while they work on a fix and agree on the time of disclosure with
you. If you wish, the fix credits you.

## Supported versions

Fixes go into the latest release of each repository: `YY.MM.N` for templates
and packages, Semantic Versioning for the `tools-*` repositories. Older
releases get no fixes. Existing instances of a template receive a fix with
`cruft update`.

## Scope

In scope are the code and configuration in the `ifdd-de` repositories and the
instances the templates generate, as shipped.

Out of scope:

- vulnerabilities in upstream images and third-party packages: please report
  them upstream; IFDD moves to fixed versions once they exist;
- installations that others operate.

Do not test against systems that you do not operate yourself.
