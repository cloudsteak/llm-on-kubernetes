Upgrade
Home
Chart Release "qdrant" successfully created.
qdrant
Description
Version
App Version
qdrant
Qdrant - Vector Database for the next generation of AI applications.
1.13.4
qdrant

Installation complete!

You're using Lens Personal (for individuals or companies with < $10M annual revenue or funding)
docker-desktop (v1.31.4)
✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔✔~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~
Helm Chart Install
NAME: qdrant
LAST DEPLOYED: Wed Mar 19 16:59:20 2025
NAMESPACE: qdrant
STATUS: deployed
REVISION: 1
NOTES:
Qdrant v1.13.4 has been deployed successfully.

The full Qdrant documentation is available at https://qdrant.tech/documentation/.

To forward Qdrant's ports execute one of the following commands:
  export POD_NAME=$(kubectl get pods --namespace qdrant -l "app.kubernetes.io/name=qdrant,app.kubernetes.io/instance=qdrant" -o jsonpath="{.items[0].metadata.name}")

If you want to use Qdrant via http execute the following commands
  kubectl --namespace qdrant port-forward $POD_NAME 6333:6333

If you want to use Qdrant via grpc execute the following commands
  kubectl --namespace qdrant port-forward $POD_NAME 6334:6334

If you want to use Qdrant via p2p execute the following commands
  kubectl --namespace qdrant port-forward $POD_NAME 6335:6335
