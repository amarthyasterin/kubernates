# kubernates
pods
--------
> pod are the smallest most diployable bjects in kubernates.
> a pod represent a singleinstance of running process in your cluster.

to list your all ports 
---------------------------
kubectl get pods  ---cmd

listing about pods info 
----------------------------- 
kubectl get pods -o wide


for applying the yml script
--------------------------------
kubectl apply -f filename.yml

pod defenition componets
-------------------------
when we creating kubernates defenition file we must have to include 4 propperty

> apiVersion 
> kind
> metadata
> spec
these are the top level or root level properties of defenition file

--------------------------------------------------------

pod  -v1
service-v1
replicationcontroller-v1
replicaset-apps/v1
deployment-apps/v1
