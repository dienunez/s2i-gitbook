# s2i-gitbook



oc new-app dienun/gitbook:2.6.9~https://github.com/somegitbookrepo/gb.git --name gitbook-pod
oc expose svc/gitbook-pod
