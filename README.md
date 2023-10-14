# Container-based CI/CD system

Using multi-stage build approach to build, unit test, e2e test, and deploy fullstack application.

Intended for an Angular application, but could be used for any fullstack technology.

The container is hosted in a deployment host, such as CircleCI or Azure. When build is successful, it will be deployed by the host.

The project name could be added dynamically as an environmental variable.

TODO:: complete Cypress e2e tests. The Chrome infrastructure has been added, but not tests have been created, so the build will fail at this stage. (e2e testing isn't always included in CI/CD chains, so this stage is optional.)
