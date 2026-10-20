# Security policy

This policy covers every public srcplugins repository that has no `SECURITY.md` of its own.

## Reporting a vulnerability

Please report security issues privately, not in a public issue:

- On GitHub, open the repository's **Security** tab and choose **Report a vulnerability**, or
- Email [contact@srcplugins.com](mailto:contact@srcplugins.com) with "Security" in the subject.

Include which repository it concerns and the version you use (for a plugin, the Build line on its settings page; for the test framework, the tag you installed), what you found and how to reproduce it. Please don't test against Jira sites or data you don't own.

We'll confirm we received your report, keep you updated while we investigate, and credit you in the release notes if you'd like.

## Supported versions

Only the latest release of each plugin and of the test framework receives security fixes. Atlassian Forge updates plugin installations automatically, except when a fix needs new permissions: then a site administrator has to approve the update. To get a fix in the test framework, move your pin to the new tag.

## Contributions

We don't accept pull requests at the moment. Bug reports and feature requests are welcome as issues.
