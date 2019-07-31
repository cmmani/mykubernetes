

DashBoard Console with Storage and metrics:

    Storage Engine

     # kubectl create -f influxdb.yaml

    Metrics Collection

     # kubectl create -f heapster.yaml

    Web UI

     # kubectl create -f dasboard.yaml

    Admin for Dashboard Access

     # kubectl apply -f dashboard-admin.yaml

     # kubectl describe sa admin-user -n kube-system
     
     # kubectl describe secret ***name of the token***  -n kube-system

