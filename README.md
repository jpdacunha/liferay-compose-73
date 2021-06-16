# liferay-compose-73
Docker compose for non clustered Liferay project (e.g: for development use only)

## Prerequisites
1. Properly install docker (tested with docker 20.10.7)
2. Properly install docker-compose (tested with docker compose 1.28.4)

## Quick Start :
1. Setup permissions on sh files
    ```console
     find ./ -name "*.sh" -exec chmod +x {} \;
    ```
2. Start docker compose in detached mode
    ```console
     sudo docker-compose -d up
    ```

## Tips :
1. Remove all container and volumes create by **this** docker compose file 
    ```console
     sudo docker-compose rm -s -v
    ```
2. Manage your containers using portainer
    ```console
     ./liferay-compose-73/utils/portainer-start.sh
    ```
