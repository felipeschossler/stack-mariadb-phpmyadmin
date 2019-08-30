# Sample Stack MariaDB

This is a simple stack for running MariaDB database. Using PHPMyAdmin to facilitate managing and usingyour DB.

## How to use this

For use this you need to install Docker and Docker Compose. If you are running on **Windows** it doesn't need to install the Docker Compose.

### Install Compose

For install Docker Compose you just need execute 2 commands:

- This first download the binaries of Docker Compose to the folder /usr/local/bin/docker-compose

```bash
sudo curl -L "https://github.com/docker/compose/releases/download/1.24.1/docker-compose-$(uname -s)-$(uname -m)" -o /usr/local/bin/docker-compose
```

- This other command gives execution permission to the Docker Compose

```
sudo chmod +x /usr/local/bin/docker-compose
```

## Using the stack

For using the stack is so simple that nether me understand how someone do this in another way.

It's just use the command (in the same folder of the file docker-compose.yml):

```bash
docker-compose up -d
```

And voilá, your stack is up and running. For acessing your PHPMyAdmin you just need using the link: http://localhost

The user and password are this:

**User:** root

**Password:** Passwd123

If something doesn't work it probably there some app running in your port 80.
