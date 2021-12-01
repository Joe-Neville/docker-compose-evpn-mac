# docker-compose-evpn-mac

1. docker compose file to create a alpine container. This can act as a source MAC for a BGP EVPN demo setup.

2. Use the following command to create multiple containers at once

    ```
    docker-compose up --scale evpn=5
    ```