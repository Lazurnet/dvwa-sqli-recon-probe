# dvwa-sqli-recon

Mini-projet d’audit de sécurité visant à détecter et exploiter une vulnérabilité d’injection SQL sur DVWA, dans le cadre d’un exercice de reconnaissance active inspiré du module NetAcad.


##  Objectifs
- Déployer un environnement vulnérable (DVWA)
- Réaliser un test d’injection SQL basique
- Comprendre et documenter la vulnérabilité
- Explorer une exploitation simple
- Présenter les méthodes d’atténuation


##  Environnement
- Kali Linux (VirtualBox)
- Docker installé
- DVWA via Docker

## Installation de DVWA

```
docker run --rm -it -p 80:80 vulnerables/web-dvwa
 
