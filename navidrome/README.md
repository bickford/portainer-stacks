# Navidrome stack
Contains Docker config for my Navidrome build.

My configuration uses a persistent volume for the Navidrome app&db data; as well as a mapped SMB drive for my media.
It also enables LastFM and Spotify integration, with environmental variables used to protect private information.
It's based on the default example Navidrome docker-compose.yml from the installation tutorial URL below.

-------

Source: https://hub.docker.com/r/deluan/navidrome
Source code: https://github.com/navidrome/navidrome
Official homepage: https://www.navidrome.org/
Tutorial: https://www.youtube.com/watch?v=47ZZpJebiG0 & https://www.navidrome.org/docs/installation/docker/