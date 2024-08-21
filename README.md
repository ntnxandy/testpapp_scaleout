# testpapp_scaleout
added
spec:
  replicas: 3
  strategy:
    type: RolllingUpdate
    rollingUpdate:
      maxSurge: 25%
      maxUnavailable: 25%
      
