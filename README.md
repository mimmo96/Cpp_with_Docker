# C++ on Docker
Tools for running Cpp applications on Docker with docker-compose and local volume


### how to run

```bash
docker build -t my_user .
```

### after the process has finish run:

```
docker run -it -v /absolute/path/local/directory:/home/my_user/Documents/ my_user bash
```
