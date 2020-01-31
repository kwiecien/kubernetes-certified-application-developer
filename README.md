# Notes
## Edit Pods
 - extract the definition, delete the Pod, re-create 
   ```
   kubectl get pod <pod-name> -o yaml > pod-definition.yaml
   kubectl delete pod <pod-name>
   kubectl create -f pod-definition.yaml
   ```
 - edit the Pod properties
   ```
   kubectl edit pod <pod-name>
   ```
