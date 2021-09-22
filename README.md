### Argo workflows
Workflow engine that orchestrate complex jobs in kubernetes clusters.

### Applications
- Data ingestion (excels, catalogs).
- Data statistics (count, analyze and interpret records).
- Maintenance jobs (cleaning, backups, stability tests).
- Machine Learning training (feature engineering, cross-validation, model training, batch inference).
- Continous Integration.

### Features
- Parallelize intensive jobs using thousands of pods.
- Pipelines, run multiple tasks sequentially.
- Directed Acyclic Graph (DAG), run tasks in dependence to other tasks.
- Cron workflows, schedule workflows at specified hours or intervals.
- Events, trigger workflows from on external events.
- Artifacts, pass the results of one task to another.
- Archives, keep history of completed workflows.

### Instalation
Kubernetes cluster (Minikube, Docker for desktop, GKE, EC2)  
kubernetes CLI (kubectl)  
`kubectl cluster-info`  
`kubectl apply -n default -f https://raw.githubusercontent.com/argoproj/argo-workflows/master/manifests/quick-start-postgres.yaml`  
`kubectl get pods –n default | grep argo`  

### Examples
1. Job types
2. Steps
3. Directed acyclic graphs
4. Parameters
5. Artifacts
6. Cronworkflows
7. Parallelization
