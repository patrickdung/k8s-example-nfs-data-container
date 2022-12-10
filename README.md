# NFS-exporter container with a file

This is an modified version of 
https://github.com/kubernetes/examples/tree/master/staging/volumes/nfs/nfs-data

This container exports /exports with index.html in it via NFS. Based on
../exports. Since some Linux kernels have issues running NFSv4 daemons in containers,
only NFSv3 is opened in this container.
