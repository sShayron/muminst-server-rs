# muminst-server-rs

This is the muminst server implementation in rust.

This is currently a work in progress, and many features are still unstable. Follow up on the feature compatibility list to get familiar with ongoing progress:

- [x] dotenv 
- [x] Logger
- [ ] Storage
- [-] Modularized
- [-] HTTP Server
    - [ ] GET /sounds
    - [ ] GET /assets
    - [ ] GET /downloads-sounds
    - [ ] POST /play-sound
    - [ ] POST /upload
    - [ ] POST /add-tags/:id
- [ ] Websocket Server
    - [ ] /ws route
        - [ ] Notifies locked state to clients
        - [ ] Manages connections correctly
- [-] Discord Client
    - [ ] Enable consumers to play audio outside of a command function. _(e.g.: from an endpoint handler)_