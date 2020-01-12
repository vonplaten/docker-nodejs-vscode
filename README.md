# NodeJS development environment with VSCode and Docker

## Description
Development environment for NodeJS. Any OS.
The folder .devcontainer is for editor VSCode.

## Run
- "docker-compose up --build" to test the container, then "docker-compose down" to shut down.
- In .devcontainer/docker-compose.yml change volume workpace dir setting to your local workspace
- Open root in VSCode. Inside VSCode Command Pallet run "reopen in container".
- remove express from package.json if not used
- npm install
