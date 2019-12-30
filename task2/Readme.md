The task contains yaml manifests with intentional errors to be troubleshooted during the second workshop task.

Please, make sure you have deleted previous task materials via `kubectl --conext=sandbox delete namespace <your name>-task1-test-workshop`

Task instructions:
- create k8s namespace for the task with name `<your name>-task2-test-workshop`
- deploy k8s manifests with `kubectl apply -f <dir>`
- find and fix all mistakes in the task yaml manifests
