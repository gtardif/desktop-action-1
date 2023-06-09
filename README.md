# desktop-action

Github Action to start Docker Desktop.

This github action is [experimental](https://docs.docker.com/release-lifecycle/#experimental).
It currently supports starting Docker Desktop on "mac" nodes in Github Actions

In your gihub action workflow, you can add a step:

```
  steps:
      - id: start_desktop
        uses: docker/desktop-action/start@0.0.1
```

After this step executes, Docker Desktop is ready and available, the docker CLI can be executed in subsequent "run" steps
