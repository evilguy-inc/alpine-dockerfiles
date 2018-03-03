# Alpine + Angular Cli

Minimalistic Alpine linux with Angular Cli 240MB

1. publish to docker
```bash
  docker build --rm -f alpine-angular-cli/Dockerfile -t alpine-angular-cli:latest alpine-angular-cli
  docker tag alpine-angular-cli:latest evilguy/angular-cli:0.1
  docker tag alpine-angular-cli:latest evilguy/angular-cli:latest
  docker push evilguy/angular-cli:0.1
  docker push evilguy/angular-cli:latest
```