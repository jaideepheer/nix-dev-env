# nix-dev-env

VSCode devcontainer with Nix package manager, running inside Alpine docker image

## Pre-Requisites

- [Visual Studio Code](https://code.visualstudio.com/)
- [Docker](https://www.docker.com/get-started/)

## Usage

- Create your own repo. from template
- Clone your repo.
- Make sure Docker Desktop/daemon is running
- Open repo. folder with VSCode
- Install recommended extensions in VSCode
- Press `Ctrl+Shift+P` VSCode
- Search and select `Devcontainers: Reopen Folder in Container`

> To change tools/software inside devenvironment, update the flake.nix file as per requirement