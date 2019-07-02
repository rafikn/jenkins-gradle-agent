# jenkins-gradle-agent

Docker image running gradle with uid 10000.
<br/>
UID value can also be set in the pod template
```
...
securityContext:
  runAsUser: 10000
  ...
```

Comes with a docker client for jobs that need it.
