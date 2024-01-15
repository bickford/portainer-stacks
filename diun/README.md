# Diun stack
Contains Docker config for my Diun build, uses external (pre-existing) data volume.

My configuration is set to have Diun run once daily, notification emails are sent for Containers that have updated images available.
All containers are monitored by Diun, and updated in Portainer (semi-automatically with manual selection), or Docker command line manually.
Portainer itself is monitored and updated automatically by Watchtower on a two-weekly schedule.
Diun is now also set to be udpated automatically by Watchtower on two-weekly schedule.

-------

Source: https://hub.docker.com/r/crazymax/diun/
Source code: https://github.com/crazy-max/diun
Official homepage: https://crazymax.dev/diun/
Tutorial: 