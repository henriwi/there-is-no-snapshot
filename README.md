# there-is-no-snapshot
Gradle + Build pipeline. Example project for the presentation "There is no snapshot"

## Run
```docker build -t nosnaps .```

```docker run --rm -p 8080:8080 -v $(pwd)/jenkins_home:/var/jenkins_home --name nosnaps nosnaps```
