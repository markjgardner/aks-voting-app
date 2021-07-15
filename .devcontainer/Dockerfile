FROM mcr.microsoft.com/vscode/devcontainers/dotnet:5.0
RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
    && apt-get -y install --no-install-recommends snapd
RUN snap install yq