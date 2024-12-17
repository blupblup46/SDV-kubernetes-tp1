   
OK- Les variables d’environnements et données d’authentification seront stockées dans des ConfigMap et Secrets.
OK- Le serveur web et le serveur BDD doivent communiquer entre eux.
OK- Le serveur BDD doit avoir un Persistent Volume Claim attaché pour permettre la persistance des données.
OK- Le serveur web et le collecteur de logs doivent exister dans le même pod (2 conteneurs).
OK- Le serveur web doit être accessible via un service de type LoadBalancer.
OK- Le collecteur de log et le serveur web doivent communiquer entre eux.
OK- Tous les pods doivent avoir des limites de ressources pour le supprimer si dysfonctionnement.
OK- Le serveur BDD n’est accessible qu’à l’intérieur du cluster, il doit être dans un pod et namespace différent car il pourrait être réutilisé par de nouvelles applications dans le futur.