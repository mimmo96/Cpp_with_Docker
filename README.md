# C++ on Docker
Tools for running Cpp applications on Docker with docker-compose and local volume


### how to run

```bash
docker-compose build
```

### after the process has finish run:

```
docker run -it -v ./data:/home/my_user/Documents/ my_user bash
```
