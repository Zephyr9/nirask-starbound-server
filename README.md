# nirask-starbound-server
Docker container for a Starbound Server

This Docker container contains the following configuration in order to get a Starbound server running, listening, and integrated with a web-facing update utility.

  * Installs Steam CMD utilities
  * Updates the Starbound server application (if nothing, installs fresh)
  * QOL server-side countdown before a server shutdown, to warn players.
  * TODO: Notify the update_app_build Docker container's build service when the server is up and running; also report errors.
