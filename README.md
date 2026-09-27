Based off https://github.com/community-valheim-tools/valheim-server-docker
This is a good generic config that simply needs updating for preferences.

It is designed to have base details\volumes in the compose file, and everything else in the .env file.

Change paths to storage.
Create directories.
Make a discord webhook to chirp user spawns.
Kick it off.

To change running game details, add -console to your steam command, hit F5 when connected to server:

setworldmodifier raids none
setworldmodifier portals casual
save

The above still allows achievements.
