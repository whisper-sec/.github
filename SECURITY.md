# Security Policy

This is the default security policy for the public repositories of Whisper Security
(viaGraph B.V.). An individual repository may ship its own `SECURITY.md` with
project-specific detail; where it does, that file takes precedence for that repository.

## Reporting a vulnerability

Please report security issues responsibly and privately to:

**security@whisper.security**

Include enough detail to reproduce the issue. We will acknowledge your report, work
with you on a fix and a disclosure timeline, and credit you if you wish. Please do not
open a public issue for security-sensitive reports.

## Verifying signed releases

Release binaries of the `whisper` CLI are published as signed, checksummed artifacts.
Each carries a SHA-256 checksum and a detached PGP signature made with the AS219419
release key (public key at <https://as219419.net/>). The full verification steps live in
the CLI's own policy: <https://github.com/whisper-sec/whisper-cli/blob/main/SECURITY.md>.

## Supported versions

Security fixes target the latest published release of each project. Please upgrade to the
most recent version before reporting an issue.
