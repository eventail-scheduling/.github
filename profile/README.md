# Eventail

Eventail runs the program side of a conference: the call for papers, accepting and confirming
sessions, and the schedule. You host it yourself, and your website or app reads the published
schedule from Eventail's API.

**[Documentation](https://eventail-scheduling.github.io/eventail-docs/)**: introduction,
self-hosting with Docker Compose or Kubernetes, showing the schedule on your website, and the
configuration and API reference.

| Repository                        | What it holds                                                                 |
| --------------------------------- | ----------------------------------------------------------------------------- |
| [eventail]                        | The API, its background worker and the web app                                |
| [eventail-deploy]                 | The Helm charts and the Docker Compose setup                                  |
| [eventail-furry-schedule-adapter] | The adapter that publishes an edition's schedule in the Furry Schedule Schema |
| [eventail-docs]                   | The documentation site                                                        |

[eventail]: https://github.com/eventail-scheduling/eventail
[eventail-deploy]: https://github.com/eventail-scheduling/eventail-deploy
[eventail-furry-schedule-adapter]: https://github.com/eventail-scheduling/eventail-furry-schedule-adapter
[eventail-docs]: https://github.com/eventail-scheduling/eventail-docs

Everything is licensed under the Apache License 2.0.
