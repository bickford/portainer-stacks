# Diun stack
Contains Docker config for my Diun build, uses external (pre-existing) data volume.

My configuration is set to have Diun run once a fortnight.
All containers are monitored by Diun, and updated in Portainer (semi-automatically with manual selection), or Docker command line manually.
Portainer itself is monitored and updated automatically by Watchtower on a monthly schedule.

-------

Source: https://hub.docker.com/r/crazymax/diun/
Source code: https://github.com/crazy-max/diun
Official homepage: https://crazymax.dev/diun/
Tutorial: 