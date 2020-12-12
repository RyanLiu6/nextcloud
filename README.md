# nextcloud

# Setup
1. Clone the repo
2. Create `.env` with:

```
CLOUD_DOMAIN=<nextcloud domain>
```

3. Create `db.env` with:

```
MYSQL_PASSWORD=<PASSWORD>
MYSQL_DATABASE=nextcloud
MYSQL_USER=nextcloud
MYSQL_ROOT_PASSWORD=<PASSWORD>
```

4. Run it!

```
docker-compose -f docker-compose.traefik.yml up -d
```
