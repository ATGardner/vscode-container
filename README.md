# vscode-container

This is just a minimal sample that demonstrates VSCode's ability to develop inside a container.  
I followed along instructions from [Developing inside a Container](https://code.visualstudio.com/docs/remote/containers) and created the simplest Python app possible.  

Usage:  
1. Open folder in VSCode
1. Install the [Remote Development extension pack](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack) as suggested
1. Re-open the folder inside the container

While "inside the container", every run/debug/pip/pytest/etc. command is being executed in the container. And no further configuration is needed to get everything to just work.
Further configuration for git authentication, volume mapping, port mapping, etc. can all be set up by editing the `.devcontainer/devcontainer.json` and `.devcontainer/Dockerfile` files.
