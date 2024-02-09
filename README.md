# Hacking_Notes
Memo outils et usages

## Table des Matières

- [Analyse de Vulnérabilités](#analyse-de-vulnérabilités)
- [Test de Pénétration](#test-de-pénétration)
- [Outils d'Analyse de Code](#outils-danalyse-de-code)
- [Proxy et Interception](#proxy-et-interception)
- [Outils Cryptographiques](#outils-cryptographiques)
- [Scripts et Outils Divers](#scripts-et-outils-divers)

## Analyse de Vulnérabilités

### Outils Basés sur le Navigateur

- **Qualys SSL Labs (SSL Test)**: Un service gratuit qui effectue une analyse détaillée de la configuration de SSL/TLS de votre serveur web.
  - Accès: [Qualys SSL Labs](https://www.ssllabs.com/ssltest/)

- **SecurityHeaders**: Évalue rapidement les en-têtes HTTP de sécurité de votre site web.
  - Accès: [Security Headers](https://securityheaders.com/)

### Outils à Installer

- **OWASP ZAP (Zed Attack Proxy)**: Un outil open-source pour tester automatiquement la sécurité des applications web.
  - Installation: Disponible sur [OWASP ZAP](https://www.zaproxy.org/download/)

- **Nikto**: Un scanner de serveur web qui teste les serveurs web pour trouver des logiciels dangereux, des fichiers mal configurés, et d'autres problèmes.
  - Installation: Instructions sur [GitHub](https://github.com/sullo/nikto)

## Test de Pénétration

### Outils Basés sur le Navigateur

- **Pentest-Tools.com**: Offre une gamme d'outils de test de pénétration en ligne pour scanner les sites web et trouver des vulnérabilités.
  - Accès: [Pentest-Tools.com](https://pentest-tools.com/)

- **Hackertarget**: Fournit des outils de test de pénétration et de scan de réseau en ligne.
  - Accès: [Hacker Target](https://hackertarget.com/)

### Outils à Installer

- **Metasploit Framework**: Un outil avancé pour développer et exécuter des exploits contre une machine distante.
  - Installation: Disponible sur [Metasploit](https://www.metasploit.com/download)

- **Burp Suite**: Une suite intégrée de tests de pénétration pour les applications web.
  - Installation: Disponible sur [PortSwigger](https://portswigger.net/burp/communitydownload)

## Outils d'Analyse de Code

### Outils Basés sur le Navigateur

- **SonarCloud**: Version cloud de SonarQube pour l'analyse de code continu.
  - Accès: [SonarCloud](https://sonarcloud.io/)

- **Codacy**: Plateforme automatisée de revue de code qui identifie les problèmes de sécurité, de performance, et de fiabilité.
  - Accès: [Codacy](https://www.codacy.com/)

### Outils à Installer

- **SonarQube**: Analyse de code source pour détecter les bugs, les vulnérabilités et les mauvaises pratiques de codage dans plus de 20 langages de programmation.
  - Installation: Instructions sur [SonarQube](https://www.sonarqube.org/downloads/)

- **Fortify**: Un outil d'analyse statique qui identifie les vulnérabilités dans le code source.
  - Installation: Détails disponibles sur le [site officiel de Fortify](https://www.microfocus.com/en-us/cyberres/application-security/static-code-analyzer)

## Proxy et Interception

### Outils Basés sur le Navigateur

- **WebScarab**: Un framework pour l'analyse des applications qui communiquent en utilisant le protocole HTTP et HTTPS.
  - Accès: WebScarab est désormais une partie de OWASP ZAP, accessible via [OWASP ZAP](https://www.zaproxy.org/docs/desktop/addons/webscarab/)

### Outils à Installer

- **Fiddler**: Un proxy web gratuit qui permet d'inspecter le trafic HTTP, de définir des points d'arrêt, et de manipuler les données.
  - Installation: Disponible sur [Telerik](https://www.telerik.com/download/fiddler)

- **Wireshark**: Un analyseur de réseau qui permet de capturer et d'interagir en temps réel avec le trafic Internet.
  - Installation: Disponible sur [Wireshark](https://www.wireshark.org/download.html)

## Outils Cryptographiques

### Outils Basés sur le Navigateur

- **Cryptr**: Un outil simple et pratique pour chiffrer et déchiffrer des textes directement dans votre navigateur.
  - Accès: [Cryptr](https://cryptr.co/)

### Outils à Installer

- **Gpg4win**: Un ensemble d'outils de cryptographie pour Windows, incluant GnuPG, Kleopatra, et d'autres outils pour le chiffrement et la signature.
  - Installation: Disponible sur [Gpg4win](https://www.gpg4win.org/download.html)

- **OpenSSL**: Un outil robuste, complet et open-source pour les applications SSL/TLS.
  - Installation: Instructions sur [OpenSSL](https://www.openssl.org/source/)

## Scripts et Outils Divers

### Outils Basés sur le Navigateur

- **Regex101**: Un outil en ligne pour tester vos expressions régulières dans différents moteurs de regex.
  - Accès: [Regex101](https://regex101.com/)

### Outils à Installer

- **Nmap**: Un outil de cartographie réseau utilisé pour découvrir des hôtes et des services sur un réseau informatique.
  - Installation: Disponible sur [Nmap](https://nmap.org/download.html)

- **John the Ripper**: Un outil de craquage de mots de passe rapide.
  - Installation: Instructions sur [Openwall](https://www.openwall.com/john/)

