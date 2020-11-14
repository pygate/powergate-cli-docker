# Powergate CLI - Docker

A dockerrized version of powergate cli just to be used in an isolated environment.

To build a specific version of the cli run:
```
docker build --build-arg POWERGATE_CLI_VERSION=<VERSION_NUMBER> . -t pygate/powergate-cli:<VERSION_NUMBER>
```

Example:
```
docker build --build-arg POWERGATE_CLI_VERSION=v1.2.1 . -t pygate/powergate-cli:v1.2.1
```