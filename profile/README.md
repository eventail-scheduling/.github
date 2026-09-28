# Eventail

Eventail runs the program side of a conference: the call for papers, accepting and confirming
sessions, and the schedule. You host it yourself, and your website or app reads the published
schedule from Eventail's API.

**[Documentation](https://eventail-scheduling.github.io/eventail-docs/)**: introduction,
self-hosting with Docker Compose or Kubernetes, showing the schedule on your website, and the
configuration and API reference.

| Repository                                                                | What it holds                                               |
| ------------------------------------------------------------------------- | ----------------------------------------------------------- |
| [eventail-api](https://github.com/eventail-scheduling/eventail-api)       | The API and its background worker                           |
| [eventail-web](https://github.com/eventail-scheduling/eventail-web)       | The web app for submitting sessions and running the program |
| [eventail-deploy](https://github.com/eventail-scheduling/eventail-deploy) | The Helm chart and the Docker Compose setup                 |
| [eventail-docs](https://github.com/eventail-scheduling/eventail-docs)     | The documentation site                                      |

Everything is licensed under the Apache License 2.0.
