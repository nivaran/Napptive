# Jenkins Application

> Jenkins Automation Server

## References
* https://www.jenkins.io/

After deploy Jenkins, ask for application info to know its endpoint executing:

```
$ playground apps info jenkins
NAME         STATUS
jenkins      RUNNING

COMPONENT    STATUS    SCOPES    TRAITS
jenkins      RUNNING             storage, napptive-ingress, resource

COMPONENT    INGRESSES
jenkins      jenkins-<username>.apps.playground.napptive.dev

POLICY                TYPE
healthscope-policy    health

```

```
open the INGRESSES endpoint link to get jenkins web
To get Inital Admin Password for jenkins  >   playground apps logs jenkins

```