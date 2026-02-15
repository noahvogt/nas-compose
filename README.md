# nas-compose

A collection of docker-compose files intended to be used by the OpenMediaVault Compose Plugin on a NAS/Homeserver.

To run these services, replace the following example values with production values in the global environment variables file:

|Environment Variable|Value|
|---|---|
|TZ|Europe/Berlin|
|UID|1000|
|GID|1000|
|PIHOLE_WEBPASSWORD|example_password|
|PIHOLE_LOCAL_IP|192.168.1.2|
|NEXTCLOUD_MARIADB_ROOT_PW|example_password|
|NEXTCLOUD_DB_PW|example_password|
|NEXTCLOUD_ADMIN_PW|example_password|
|NEXTCLOUD_TRUSTED_DOMAIN|nextcloud.example.org|
|MQTT_USER|example|
|MQTT_PASSWORD|example_password|
|WIKI_DB_PASS|example_password|
|WP_DB_ROOT_PW|example_password|
|WP_DB_USER_PW|example_password|
|FORGEJO_DOMAIN|git.example.org|
|FORGEJO_ROOT_URL|https://git.example.org/|
