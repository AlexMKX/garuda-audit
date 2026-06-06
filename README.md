# conntrack_log image

Build context for `ghcr.io/alexmkx/garuda-conntrack-log` — a minimal
Alpine + conntrack-tools sidecar image used by `modules/firezone/kube`
to log new connections (`conntrack -E -e NEW`). Published by
`.github/workflows/publish-images.yml`.
