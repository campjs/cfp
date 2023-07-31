# cfp

Contains a deployment of [Pretalx](https://pretalx.com) for CampJS.

The pretalx container comes from [thepatrick/pretalx-docker](https://github.com/thepatrick/pretalx-docker), the only changes from upstream are:

1. builds an arm64 container (doing this on github actions currently fails, you'll need an arm64 machine to do this)
2. binds to 0.0.0.0:80 instead of the default 127.0.0.1:80, this was necessary for traefik in my environment.

## Interested in helping out?

Anything related to this please reach out to me ([@patrick](https://github.com/thepatrick)), for CampJS check out the latest event at [campjs.com](https://campjs.com/)
