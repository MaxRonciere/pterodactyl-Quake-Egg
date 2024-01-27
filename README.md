# pterodactyl-Quake-Egg
## Quake 3 Arena Egg for pterodactyl

- download and install the egg
- add all the server.cfg file as `./baseq3/server.cfg`.
- It is a good practice to add your game, bots and maps configuration in externals files
- personally I use : `./baseq3/config/<FILENAME>.cfg` for thoses.
- You can add extra configuration file with `+exec`

## How to use it

Configure your server as normal.

> `512 MB` of Ram and of storage is enough.

The server port and ram size are set at startup as well as default map.
Add your `.pak` files to `./baseq3` as well as your `.cfg` files.

## Future plan

Ounce I have understood how the `text` parser of pterodactyl works, I will add a proper server.cfg configuration.
Which will include pterodactyl variables for password, motd etc.
