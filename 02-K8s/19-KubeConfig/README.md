```
   10  mkdir .kube
   11  vim .kube/config
   12  kubectl  get nodes
   13  ls
   14  mv .kube/config myk8s-cluster
   15  kubectl  get nodes
   16  ls
   17  kubectl  get nodes --kubeconfig=myk8s-cluster
   18  kubectl config get-context --kubeconfig=myk8s-cluster
   19  kubectl config get-contexts --kubeconfig=myk8s-cluster
   20  cp -rf myk8s-cluster .kube/config
   21  ls
   22  kubectl config get-contexts
   23  vim .kube/config
   24  ls
   25  cat .kube/config
   26  > .kube/config
   27  vim .kube/config
   28  kubectl config get-contexts
   35  kubectl  get nodes
   36  kubectl  get pods
   37  ls
   38  kubectl config get-contexts
   61  kubectl config set-context amit@gcp  --cluster=gcp --user=amit
   62  kubectl config get-contexts
   63  kubectl config use-context amit@gcp
   64  kubectl config get-contexts
   65  kubectl get nodes
```
