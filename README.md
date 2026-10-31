# Enki runtime binaries

This repository distributes compiled Enki companion-runtime binaries and their
license notices. The daemon and inference-worker implementation source remains
private. The separately licensed MIT client SDK is not the daemon implementation.

Runtime binaries may be bundled with tomblanchard312 applications under
[BINARY-DISTRIBUTION-LICENSE.txt](BINARY-DISTRIBUTION-LICENSE.txt).
Third-party software, branding and model licenses remain separate. Model weights
are not included.

Releases contain platform-specific binary archives, runtime identity metadata and
SHA-256 checksums. App builds pin an exact archive checksum. No daemon or worker
source, private Git history, debug-symbol bundle or source archive is published.
Only platforms with an actual compiled archive can be bundled; missing platform
artifacts must block packaging rather than silently omit the runtime.

Preview releases are for integration review and are not native-platform release
acceptance. This repository's automatic GitHub source archives contain only this
README and license notices.
