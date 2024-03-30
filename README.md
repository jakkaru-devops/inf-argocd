ArgoCD Applications per EKS Cluster

Name of the folder represent name of the EKS Cluster (Except HelmCharts).

│
├── HelmCharts             # All Helm Charts asdsadsdfds
│   ├── ChartTest1
│   │   ├── Chart.yaml
│   │   ├── templates
│   │   └── values.yaml        # Default Values
│   └── ChartTest2
│       ├── Chart.yaml
│       ├── templates
│       └── values.yaml        # Default Values
│   
├── demo-dev                   # EKS Cluster name
│   ├── applications
│   │   ├── app1.yaml
│   │   └── app2.yaml
│   └── root.yaml              # Root ArgoCD Application
└── demo-prod                  # EKS Cluster name
    ├── applications
    │   ├── app1.yaml
    │   └── app2.yaml
    └── root.yaml              # Root ArgoCD Application    
