# Architectural Requirements

- Zero coupling between child projects
- Near-zero coupling between Container and child apps
- CSS from one projects should not affect another project
- Version control (monorepo vs separate repos) should not have any impact on the overall project
- Container should be able to decide to always use the latest version of a microfrontend **or** specify a specific version
