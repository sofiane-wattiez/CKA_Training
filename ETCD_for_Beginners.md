# ETCD FOR BEGINNERS

## Intro ETCD

### Objectives :

* What is ETCD ?

    * Il s'agit d'un magasin de valeurs clés fiable et distribué, simple, sécurisé et rapide.

* What is a Key-value Store?

    * Transit des données dans l'ETCD sous format JSON (Key-value)

* How to get Started quickly ?

    * Téléchargez le répository correspondant a votre type de système d'exploitation sur  git hub  

    ````curl -L https://github.com/etcd-io/etcd/releases/download/v3.3.11/etcd-v3.3.11-linux-amd64.tar.gz -o etcd-v3.3.11-linux-amd64.tar.gz```

    * Décomprésser le fichier 

    ```tar xzvf etcd-v3.3.11-linux-amd64.tar.gz```

    * Executer L'ETCD Service

    ```./etcd```

* How to operate ETCD ?

    * Les service démarre sur le port 2379 par défault , l'ont peu ensuite attacher n'importe quel client au service ETCD pour stocker des information par défaut

    * Changer/Récuperer valeur dans l'etcd avec le cli :

        * ```./etcdctl set key1 value1```

        * ```./etcdctl get key1 value1```

    * Helper commande : ```./etcdctl```


### Later

* What is a distributed System ?

* How ETCD Operates

* RAFT Protocol

* Best practices on number of nodes 