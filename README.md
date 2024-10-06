# UE-AD-A1-TUTOGRPC

**UE AD FIL A1**

[Tutoriel sur gRPC de Helene Coullon - helene.coullon@imt-atlantique.fr](https://helene-coullon.fr/pages/ue-ad-fil-24-25/tuto-grpc/)

## Objectifs

- Initiation aux concepts de base de gRPC en mettant en place un service de films. Le TP consiste à :

1. **Créer une interface** utilisant Protocol Buffers (fichier `.proto`) pour définir les services et messages échangés entre le client et le serveur.
2. **Compiler les fichiers `.proto`** pour générer les stubs côté client et serveur.
3. **Implémenter le serveur gRPC** en surchargeant une classe pour gérer les requêtes distantes.
4. **Implémenter le client gRPC** en utilisant les stubs pour communiquer avec le serveur.
5. **Tester les services gRPC** avec des appels distants et des streams de données.
6. **Utiliser Postman** pour tester et déboguer l’API sans implémenter de client.

L’objectif final est de comprendre le fonctionnement de gRPC, en particulier comment définir, compiler, et utiliser des services via des appels distants dans un environnement client-serveur.