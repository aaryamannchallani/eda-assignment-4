# EDA A4

---

## Role: Orchestration of Microservices related to a smart power meter

---
Setup the k8s cluster(GKE):

```bash
gcloud container clusters create project-power --accelerator=[nvidia-tesla-k80,1]
```

Install Services

`kubectl apply -f ./k8s`

---
