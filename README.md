
# 🐳 MySQL with Persistent Storage & phpMyAdmin on Kubernetes

This project deploys a **MySQL database with persistent storage** on a real Kubernetes cluster. It also includes automatic **database initialization** and a **phpMyAdmin UI** to interact with the database.

---

## Project Structure
 ```
├── init-db-configmap.yaml            # SQL file for DB + table + data
├── mysql-pvc.yaml                    # PersistentVolumeClaim (uses volume from node)
├── mysql-pv.yaml                     # Assign physical Valume from local system
├── mysql-secret.yaml                 # Secure MySQL root password
├── mysql-service.yaml                # MySQL service
├── mysql-statefulset.yaml            # MySQL StatefulSet    
└── phpmyadmin-deployment.yaml        # Web-based MySQL UI
``` 
## Below are given files:
* init-db-configmap.yaml (init-db-configmap.yaml)     
* mysql-pvc.yaml              
* mysql-pv.yaml               
* mysql-secret.yaml          
* mysql-service.yaml         
* mysql-statefulset.yaml      
* phpmyadmin-deployment.yaml 
