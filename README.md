# Docker Compose Manager for Unraid (compose_plugin)
This plugin installs Docker Compose v2 on unRAID. WebGUI integration is still a work in progress.

## Settings

**Compose Project Directory**: Choose the folder in which compose.manager will store your stacks.
  - WARNING: Changing this path will not automatically move your existing project folders.

**Compose Command Progress Display**: Choose the style of output for plugin commands.
  - When set to `basic` the output will be simple text as elsewhere in the webui.
  - When set to `ttyd` the output will be a terminal window with colored text.

**Debug Logging**: Enable debug logging.

**Recreate During Autostart**: Use the --force-recreate option when autostarting stacks.
  - This will recreate each stack container on startup.
  - This can work around an issue where containers refuse to autostart because the network they are attached to no longer exists.

**Show Compose in Header Menu**: This will move the Compose Manager page to a separate tab in the Unraid Header menu.

