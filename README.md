# TP 12 : Service SOAP avec Apache CXF (JAX-WS, JAXB, WSDL, WS-Security)
## Aperçu
Dans ce lab, on conçoit un service SOAP en Java avec Apache CXF, on l’expose en local, on comprend son WSDL, on sérialise des objets avec JAXB, 
on génère/consomme un client, puis on ajoute une première couche de sécurité WS-Security (UsernameToken). Le flux suit un chemin “code-first → WSDL → test → sécurité”.

## Pré-requis
- Java 17 (ou 11+)
-  Maven 3.8+
-  un IDE Java, SoapUI.

## Tester le service avec SoapUI

<img width="1386" height="861" alt="Capture d’écran 2025-11-08 à 09 57 22" src="https://github.com/user-attachments/assets/9d425f67-c0cf-4cee-b07f-fff3e7687436" />
<img width="1386" height="861" alt="Capture d’écran 2025-11-08 à 09 57 10" src="https://github.com/user-attachments/assets/ffd645ee-ec64-4075-8d60-8e356db4b29c" />

## Ajouter WS-Security 

<img width="2940" height="1708" alt="image" src="https://github.com/user-attachments/assets/61e0602d-1dda-41f8-8649-4d88c050c130" />
<img width="2940" height="1708" alt="image" src="https://github.com/user-attachments/assets/8766740d-70a5-460b-8d57-ff3732e0adce" />

##  Conclusion
Ce TP m’a permis de comprendre comment créer et sécuriser un service SOAP avec Apache CXF en mode code-first.
J’ai appris à utiliser WS-Security (UsernameToken), à tester le service avec SoapUI, et à appliquer les bonnes pratiques de sécurité comme HTTPS et PasswordDigest.
