## todo 
todo:
argo workflow hello world
argo events webook to trigger hello world

steps:

install helm 3
helm repo add argo https://argoproj.github.io/argo-helm
install argo cli https://github.com/argoproj/argo/releases?after=v2.5.0-rc1
install crds
test hello world
kubectl apply argo-rbac - SA is provided by helm, CRB is not

todo: 
configure artifacts via s3 or minio, minio is broken in the helm chart at present for k8s 1.17 https://github.com/argoproj/argo-helm/pull/229
