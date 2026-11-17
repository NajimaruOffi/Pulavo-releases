<p align="center">
  <img src="logo.png" width="128" alt="Pulavo">
</p>

<h1 align="center">Pulavo</h1>
<p align="center"><b>Entretien, nettoyage et réglages de votre PC Windows, expliqués simplement.</b></p>

<p align="center">
  <a href="https://github.com/NajimaruOffi/Pulavo-releases/releases/latest"><b>⬇ Télécharger la dernière version</b></a>
</p>

---

## Ce que fait Pulavo

- **Entretien du mois** : un parcours guidé (nettoyage sans risque, mises à jour, bilan) en quelques minutes.
- **Désinstallation complète** : retire un logiciel puis ses restes (registre, dossiers), avec sauvegarde avant suppression.
- **Espace disque** : fichiers inutiles, gros fichiers, vrais doublons (ceux dont un logiciel a besoin sont détectés et protégés).
- **Applications** : installer, mettre à jour et désinstaller, y compris les applications du Microsoft Store.
- **Optimisation** : des profils de réglages expliqués un par un (ce que ça fait, le gain réel, le risque), réversibles.
- **Diagnostic** : protection du PC (antivirus, pare-feu, mises à jour de Windows) et santé du matériel (disques, batterie).
- **Historique et sauvegardes** : tout ce que Pulavo fait est noté, et peut être annulé pendant 30 jours.

Rien n'est fait sans votre accord, et chaque action est expliquée avec son niveau de risque.

## Installer

1. Téléchargez `PulavoSetup-x.y.z.exe` depuis la [dernière version](https://github.com/NajimaruOffi/Pulavo-releases/releases/latest).
2. Lancez-le. Windows peut afficher **« Windows a protégé votre ordinateur »** : l'installateur n'est pas encore signé
   (la signature est payante). Cliquez sur **Informations complémentaires**, puis **Exécuter quand même**.
3. Pulavo se met ensuite à jour tout seul : il vous propose chaque nouvelle version, vous choisissez quand l'installer.

Windows 10 (version 2004 ou plus récente) ou Windows 11, 64 bits. Rien d'autre à installer.

## Vérifier le fichier (facultatif)

Chaque version est publiée avec son empreinte `.sha256`. Pour vérifier le fichier téléchargé, dans PowerShell :

```powershell
Get-FileHash .\PulavoSetup-0.1.0.exe -Algorithm SHA256
```

Le résultat doit être identique au contenu du fichier `.sha256` de la même version. Pulavo fait cette vérification
automatiquement avant chaque mise à jour.

## Confidentialité

Pulavo ne collecte rien et n'envoie aucune donnée. Il se connecte à Internet uniquement pour vérifier s'il existe
une nouvelle version (ici, sur GitHub) et pour télécharger les applications que vous demandez d'installer.

---

<sub>Ce dépôt ne contient que les versions publiées de Pulavo. Le code source n'est pas public.</sub>
