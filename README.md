# Config Service Repository

This repository contains environment configurations for different deployment stages of the system.

## Environments

### `default`

- Used for **local development**.
- Automatically loaded when a developer runs the system locally.
- Primarily used by **backend developers**.

### `dev`

- Runs on the **development server**.
- Mirrors the `default` environment closely.
- Primarily used by **frontend developers** for integration.

### `sit`

- Runs on the **SIT (System Integration Testing) server**.
- Contains **cherry-picked, completed modules/features**.
- Used by the **QA team** for validation.

### `uat`

- Runs on the **UAT (User Acceptance Testing) server**.
- Closely resembles the `prod` environment.
- Used by **stakeholders** and **third-party testers**.

### `prod`

- Runs on the **production server**.
- Hosts the **final, stable product**.
- Used by **end users** in live environments.
