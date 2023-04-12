# suneditor-backend

CDC based backend for suneditor

## Concept

![alt text](https://raw.githubusercontent.com/gedw99/suneditor-backend/main/concept-01.jpg)


Left Pane is a File System view

Right Pane is a XML Properies view.

## Features

The following [features](features.md) are planned so that the system is fully featured for both local and server based editing for large projects.



## TODO

- docker build or frontend. DONE

- Server for backend and frontend. DONE

- Caddy HTTPS

- Caddy NATS hooks

- Does your JS have hooks that fire when a user mutates text or a cat image for example ?
  - Cause then i can take that hook, send it to the backend or update the backend and all other collaboritive users that the change occurred and then show it in their Sun Editor.

- CDC File system watcher
- CDC Client for CLI ( all desktops ) and Froentend ( wasm )
- Github ations releaser based on tags.
