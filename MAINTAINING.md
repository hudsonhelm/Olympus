# Maintaining the Olympus Fork

Keep `origin` pointed at the Olympus fork and `upstream` at official Hermes. Preserve history and attribution. Use `olympus/O-001-feature-name` branches for individual changes and `upstream/sync-version` branches for upstream updates. Keep sync and feature changes independently reviewable; do not force-push shared release branches.

Before integrating an upstream release, inspect its notes and changes, assess every registered patch, integrate on a dedicated branch, document compatibility and test results, and request review. Evaluate retirement when upstream supplies equivalent functionality. Do not deploy an update automatically. Record each divergence and its removal procedure in `FORK_NOTES.md` alongside its code change.
