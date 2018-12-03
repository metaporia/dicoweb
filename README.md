## Usage

Having aquired the container,
[beryj7/dicoweb:latest](https://hub.docker.com/r/beryj7/dicoweb/), configure
DICT servers—in [settings.py](./dicoweb/settings.py)—add host(s) to
DICT_SERVERS, and launch the dicoweb client.

```bash
docker run --name="dicoweb" --rm -d -p8000:8000 beryj7/dicoweb:latest
```

Note: default DICT hosts include: gnu.org.ua, dict.org, and a dummy local address.
