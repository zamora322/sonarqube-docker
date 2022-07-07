
# Install SonarQube Docker

Easy way for install SonarQube with Docker


## Installation

1.- From your project directory, start up your application by running

```bash
  docker compose up -d
```

2.- Enter http://localhost:9000/ in a browser to see the application running. Default user and password is:

```bash
  admin
  admin
```
    
## Windows issue - Fix



Open your CMD or PowerShell and run the following:

```bash
  wsl -d docker-desktop
  sysctl -w vm.max_map_count=262144
```
## License

[MIT](https://choosealicense.com/licenses/mit/)

