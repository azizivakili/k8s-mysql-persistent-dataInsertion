
# 🐳 MySQL with Persistent Storage & phpMyAdmin on Kubernetes

This project deploys a **MySQL database with persistent storage** on a real Kubernetes cluster. It also includes automatic **database initialization** and a **phpMyAdmin UI** to interact with the database.

---

## Project Structure
 ``` 
 ├── mysql-secret.yaml # Secure MySQL root password
 ├── mysql-pvc.yaml # PersistentVolumeClaim (uses StorageClass)
 ├── mysql-statefulset.yaml # MySQL StatefulSet
 ├── mysql-service.yaml # MySQL service
 ├── init-db-configmap.yaml # SQL file for DB + table + data
 ├── phpmyadmin-deployment.yaml # Web-based MySQL UI
 
  ``` 
