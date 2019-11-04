Setup test env:
```
cd [this-repo]
docker run -it -v$(pwd):/apps --entrypoint "/bin/sh" alpine/helm:3.0.0-rc.2
```
