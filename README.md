# Set `docker compose` Version Action

This action pins the `docker compose` version inside a GHA.

The GitHub Actions Runner is pinned to the very latest `docker compose` version.
In the past, this has silently broken many GHA pipelines due to bugs introduced
in new `docker compose` releases. You may use this action to prevent this errors
and update `docker compose` at your own pace.
