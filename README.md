# project-fa-web

The web app for Project FA, a made-up delivery company. The backend, the design and the experiments live in [project-fa](https://github.com/citrusunshiu/project-fa); this repository will hold only the web app's code.

## Status

Empty until Phase 8 of the [roadmap](https://github.com/citrusunshiu/project-fa/blob/main/docs/charter.md#roadmap). Nothing is built here before the backend it calls exists.

## What it will be

- Customer and merchant modes, in TypeScript with React (`web-app` in the [catalog](https://github.com/citrusunshiu/project-fa/blob/main/catalog/components.yaml)).
- It calls only the web backend-for-frontend, `web-bff`, which lives in the main repository with the rest of the backend.
- The group cart in the browser, where several people edit one cart at once.
- Phase 8 is done when its reports exist: concurrent cart edits merging, and the backend-for-frontend's fan-out latency.

The design doc for the clients, `docs/design/clients.md` in the main repository, is still to be written.

## Issues

Issues for this repository are filed in [project-fa](https://github.com/citrusunshiu/project-fa/issues), together with the other repositories' issues. Pull requests here link them as `Closes citrusunshiu/project-fa#N`.

## How it's made

The maintainer drafts docs and code with AI coding agents. Commits that an agent helped write say so in trailers naming the agent, its model and its effort level, as the main repository's [AGENTS.md](https://github.com/citrusunshiu/project-fa/blob/main/AGENTS.md) describes.

## Licence

[Apache-2.0](LICENSE).
