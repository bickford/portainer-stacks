# Watchtower stack
Contains Docker config for my Watchtower build, uses Docker data directly only (no volumes needed) and doesn't need to communicate with existing containers so no networks either.

My configuration is set to have Watchtower ONLY monitor and automatically-update Portainer.
Other containers are monitorer by Diun, and updated in Portainer (semi-automatically), or Docker command line manually.

-------

Source: https://hub.docker.com/r/containrrr/watchtower
Source code: https://github.com/containrrr/watchtower/
Official homepage: https://containrrr.dev/watchtower/
Tutorial: https://www.youtube.com/watch?v=5lP_pdjcVMo