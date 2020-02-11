The task contains yaml manifests to be applied during the first workshop task.
Task instructions:
* create k8s namespace for the task with name `<your name>-task1-test-workshop`
* fix ingress.yaml on spec.rules.[host] field
* deploy k8s manifests with `kubectl apply -f <dir>`
* check the app have been properly deployed:
** observe manifests on k8s via `kubectl get`
** check logs via kubectl & dash
** go to the nginx pod and `curl localhost`, `curl localhost:8080`, `curl localhost:8080/ping`, `curl localhost:8080/metrics`
** check k8s service via `curl -v <service_ip>` from the pod
** check ingress and service via curl `curl https://<ingress host>/`, `curl -v curl https://<ingress host>/` from your own machine
* Consider task done
