# git server

mrrp :3

## notes

- IMPORTANT: on first setup of a instance, forgejo might not create the repo root path automatically inside the container for some reason (which can manifest as ssh authentication errors, or "could not read repo data" errors on the web ui). to fix this, enter the container and run (as forgejo's user, e.g. `git`) `forgejo doctor check --all` and then `forgejo doctor check --fix`.
