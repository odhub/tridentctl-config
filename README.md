1. Command to running json file using tridentctl
    ./tridentctl create backend -f trident.json -n trident
3. Create storageclass using with trident as backend
   oc apply -f storage-class-nas.yaml
