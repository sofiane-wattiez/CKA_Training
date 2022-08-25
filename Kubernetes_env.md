# Synthèse Cours 1 ( CKA )

## Composant Kubernetes

* ```Kubelet``` et un agent qui s’exécute sur tous les nœuds d’un cluster

* ```Kubelet``` et comme le capitaine d’un navire qui gère les conteneurs

* Ecoute les instruction du kube api server et gère les conteneur

* ```Kube-api``` récupère périodiquement les rapports d’état de kubelet pour surveiller l’état des nœuds

* ```kube-scheduler``` : Est le responsable de la planification odes applications ou des containeur sur les nœuds
* ```Kube Controller Manager``` :
Nous avons différent contrôleur qui prenne en charge différentes fonction comme le contrôle des nœuds , réplication , contrôleur 

* ```kube-api``` : qui est le responsable de l’orchestration des opérations au seins du cluster

* ```Kube-Proxy``` : qui aide à activer la communication entre les services au sein du cluster

## ```Nœuds Master et Worker```

* Sur le Master ont a le cluster ```ETCD``` qui stocke les information (Base de données)

* Sur les Noeuds Worker ont retrouvera ```Kubelet``` et ```Kube-proxy``` pour communiquer avec le Master


