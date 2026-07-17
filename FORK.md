# Fork policy

- Keep this fork as close to upstream Gitea as possible.
- Keep the local patch set small, focused, and easy to remove.
- Keep the `upstream` branch identical to upstream; make local changes on `main`.
- Merge upstream frequently. When upstream supersedes a local patch, prefer upstream and remove the local patch.
- Discuss significant merge conflicts with the user before resolving them.
- Keep `podman build --tag gitea .` working.
