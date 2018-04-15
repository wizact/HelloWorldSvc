# Hello World Http Service
Sample project to measure the TTFHW (Time to First Hello World)

TTFHW is used as one of the metrics indicating how easy it is for a developer to get an app into production and improve it iteratively afterwards.

To Build:
```
docker build -t wizact/hello-world-svc:0.0.2 .
```

To Run:
```
 docker run -p 8080:8080 wizact/hello-world-svc:0.0.2
```

Note: You need to change te version number in the above commands.
