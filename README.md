# [Automation of Everything - How To Combine Argo Events, Workflows & Pipelines, CD, and Rollouts](https://youtu.be/XNXJtxkUKeY)

Stop eventbus
`kubectl patch eventbus/default -p '{"metadata":{"finalizers":[]}}' --type=merge -n argo-events`
