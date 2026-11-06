# Tachüller — mises à jour

Ce dépôt sert uniquement à distribuer les mises à jour de **Tachüller**, mon gestionnaire de tâches
(tableau, calendrier, rappels, post-it).

- `version.json` : la dernière version disponible. Tachüller le lit au lancement (puis toutes les 6 h).
- **Releases** : un `Tachuller.pck` par version. C'est le logiciel lui-même (~6 Mo).

Quand une nouvelle version sort, Tachüller la télécharge tout seul, vérifie son empreinte (sha256)
et l'installe à la fermeture. Il n'y a rien à faire côté utilisateur.

Pour l'installer la première fois : prendre le zip « Tachüller X.Y.Z.zip » qu'on m'a envoyé,
le dézipper et double-cliquer sur `Tachüller.exe`.
