## What is it?

This is a demo repository corresponding to the Mage ETL demo [here](http://docs.mage.ai/guides/load-api-data).

## How can I get started?

First, be sure Docker is installed and running, then run the following command:

Mac/Linux:

```bash 
git clone https://github.com/mage-ai/etl-demo mage-etl-demo \
&& cd mage-etl-demo \
&& cp dev.env .env && rm dev.env \
&& docker compose up
```

Windows:

```bash 
git clone https://github.com/mage-ai/etl-demo mage-etl-demo 
cd mage-etl-demo
cp dev.env .env
rm dev.env
docker compose up
```

## How can I access PostgreSQL?
You can access the PostgreSQL database on port 5000. We changed the port, so it won't conflict with your local PostgreSQL instance.

Credentials:
- Username: `estate`
- Password: `estate`
- Database: `estate`
- Host: `localhost`
- Port: `5000`