# Container-based CI/CD system

Using multi-stage build approach to build, unit test, e2e test, and deploy fullstack application.

Intended for an Angular application, but could be used for any fullstack technology.

The container is hosted in a cloud deployment host, such as CircleCI or Azure. When build is successful, it will be deployed by the cloud host.

The project name could be added dynamically as an environmental variable.

TODO: complete Cypress e2e tests. The Chrome infrastructure has been added and will work, but no tests have been created, so the build will fail at this stage. (e2e testing isn't always included in CI/CD chains, so this stage is optional, and could be switched on or off by an environment variable.)
