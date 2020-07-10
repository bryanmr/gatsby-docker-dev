## Instructions
Edit .env to match what you are wanting to create

UID and GID are the user you will be using to edit. On Ubuntu, the default user is GID 1000 and UID 1000.

Run `make new` to create the Docker image and run `gatsby new`. `make up` will run `docker-compose up` and put you into development mode. `make build` will build and then serve a production build.

### Running Commands
You can run a command like so:
* `docker run dev yarn add bulma node-sass gatsby-plugin-sass`

## Known Issues
On Windows with WSL if you delete the directory and then recreate again with a `make new` the mount may become stale. I worked around this by resetting Docker.
