# Installer CONCLAVE

*Pour vous qui allez installer CONCLAVE sur votre ordinateur. Aucune connaissance
technique n'est nécessaire : il suffit de suivre les étapes dans l'ordre. Comptez une
demi-heure, plus le temps de télécharger un modèle d'IA si votre ordinateur peut en faire
tourner un.*

CONCLAVE est un conseil d'experts : des intelligences artificielles qui lisent votre
dossier (vos fiches, sur votre ordinateur) et vous donnent leur avis. Il s'installe sur
**votre** ordinateur, pour vous seul. Personne d'autre n'y a accès, pas même la personne
qui vous l'a donné.

---

## 1. Ce qu'il vous faut

- **Un Mac avec une puce Apple** (M1 ou plus récent), sous macOS 13 ou plus récent ;
  **ou un PC sous Windows 10 ou 11**, 64 bits.
- **Une connexion internet**, le temps de l'installation, puis pour parler aux experts.
- **Un compte chez un fournisseur d'IA** : l'assistant de CONCLAVE vous guide pour le
  créer (partie 5). C'est lui qui fait payer les experts : de quelques euros par mois.
- Facultatif : **Ollama**, un programme gratuit qui fait tourner un modèle d'IA sur votre
  ordinateur, pour que l'entretien d'accueil et la lecture de vos documents n'en sortent
  pas. CONCLAVE vous dit si votre ordinateur est assez puissant.

## 2. Télécharger

Cliquez sur le lien de votre ordinateur :

- sur Mac : https://github.com/Thomas8343/conclave-versions/releases/latest/download/CONCLAVE-Mac.dmg
- sur PC : https://github.com/Thomas8343/conclave-versions/releases/latest/download/CONCLAVE-Windows.exe

Ces liens donnent toujours la dernière version. Le fichier arrive dans le dossier
**Téléchargements**. S'il y en a déjà un du même nom (une version précédente), le nouveau
prend un numéro, par exemple `CONCLAVE-Windows (1).exe` : prenez toujours le plus récent.
Les versions précédentes, et ce que chacune change :
https://github.com/Thomas8343/conclave-versions/releases

Sur PC, Edge peut arrêter le téléchargement en disant que CONCLAVE-Windows.exe « n'est pas
fréquemment téléchargé ». Pour garder le fichier : sur cette ligne, cliquez les trois points
(**…**), puis **Conserver** ; dans la fenêtre qui s'ouvre, cliquez **Afficher plus**, puis
**Conserver quand même**. Chrome peut aussi demander une confirmation : choisissez de
conserver le fichier.
<!-- Capture à faire : le panneau des téléchargements d'Edge. Libellés à vérifier sur un
     Windows 11 en français. -->

## 3. Installer, sur Mac

1. Double-cliquez sur le fichier `CONCLAVE-Mac.dmg` que vous venez de télécharger. Une
   fenêtre s'ouvre, avec CONCLAVE et un dossier
   Applications.
2. **Faites glisser CONCLAVE sur le dossier Applications.** Attendez la fin de la copie.
3. Fermez la fenêtre, puis éjectez le disque « CONCLAVE » (dans le Finder, la petite
   flèche à côté de son nom).

### Passer l'avertissement de macOS (une seule fois)

CONCLAVE n'est pas signé auprès d'Apple (cela coûte 99 $ par an). Au premier lancement,
macOS refuse donc de l'ouvrir. Depuis macOS 15, le clic droit puis « Ouvrir » ne suffit
plus. Voici le chemin :

1. Ouvrez le dossier **Applications** et double-cliquez sur **CONCLAVE**. macOS affiche
   un message disant qu'il ne peut pas vérifier l'application. Cliquez **Terminé** (ou
   **OK**).
   <!-- Capture à faire : le message de macOS. -->
2. Ouvrez **Réglages Système** (le menu Pomme, en haut à gauche de l'écran), puis
   **Confidentialité et sécurité**. Faites défiler jusqu'en bas : une ligne dit que
   « CONCLAVE » a été bloqué. Cliquez **Ouvrir quand même**, et donnez le mot de passe de
   votre Mac si on vous le demande.
   <!-- Capture à faire : la ligne « Ouvrir quand même ». -->
3. Double-cliquez de nouveau sur CONCLAVE, et confirmez **Ouvrir**.

Faites-le dans l'heure qui suit le premier essai : passé ce délai, le bouton peut
disparaître, et il faut recommencer à l'étape 1. Ensuite, CONCLAVE s'ouvre d'un
double-clic, sans question.

macOS peut aussi demander si CONCLAVE peut accéder à votre dossier **Documents** : c'est
là qu'il range votre dossier. Répondez **Autoriser**. La question peut revenir après une
mise à jour de CONCLAVE.

Une fois CONCLAVE installé, mettez le fichier `.dmg` téléchargé à la corbeille : il ne sert
plus.

## 4. Installer, sur PC

1. Double-cliquez sur le fichier `CONCLAVE-Windows.exe` que vous venez de télécharger.
2. **Windows a protégé votre ordinateur** : ce message bleu vient de ce que CONCLAVE n'est
   pas signé. Cliquez **Informations complémentaires** (selon la version de Windows :
   **Plus d'infos**), puis **Exécuter quand même**.
   <!-- Capture à faire : le message bleu, et le bouton « Exécuter quand même ». -->
3. L'installation se fait pour vous seul, sans mot de passe d'administrateur. L'installateur
   montre quelques pages, l'une après l'autre :
   - le dossier où installer CONCLAVE (seulement la première fois) : gardez celui proposé,
     cliquez **Suivant** ;
   - « Mettre une icône CONCLAVE sur le Bureau », cochée d'avance : décochez-la si vous n'en
     voulez pas, cliquez **Suivant** ;
   - le résumé : cliquez **Installer** ;
   - la fin, avec « Ouvrir CONCLAVE » coché : cliquez **Terminer**, CONCLAVE s'ouvre.

   <!-- Libellés à vérifier sur un vrai PC : « Suivant », « Installer » et « Terminer »
        viennent de la traduction française de l'installateur (Inno Setup), pas de
        CONCLAVE. Capture à faire. -->

Si une fenêtre dit que CONCLAVE est déjà ouvert pendant l'installation d'une nouvelle
version, laissez l'installateur le fermer (il vous le demande d'abord).

Une fois CONCLAVE installé, mettez le fichier téléchargé à la corbeille : il ne sert plus.

**Si Windows bloque CONCLAVE sans proposer « Exécuter quand même »**, c'est le **contrôle
intelligent des applications** (Smart App Control) qui est actif sur votre PC. Il bloque
toute application non signée, sans exception possible pour une seule. Le désactiver se fait
dans **Sécurité Windows**, **Contrôle des applications et du navigateur**, **Paramètres du
contrôle intelligent des applications** ; mais c'est un réglage de sécurité de tout le PC :
**parlez-en d'abord à la personne qui vous aide**, ne le faites pas seul.
<!-- Capture à faire : le message de blocage, et le réglage. -->

## 5. Le premier démarrage : l'assistant

CONCLAVE s'ouvre dans votre navigateur (Safari, Chrome, Edge…). Il n'a pas de fenêtre à lui
: c'est une page, à l'adresse `http://127.0.0.1:8765`, qui ne vient que de votre ordinateur.

La première fois, un **assistant** (la page « Bienvenue ») vous guide en six étapes.
CONCLAVE vérifie chacune et vous dit ce qui reste à faire. Vous pouvez passer une étape et
y revenir plus tard : tout reste dans l'onglet **Réglages**.

1. **Vous** — votre prénom (les experts vous appellent ainsi ; sans prénom, ils disent « la
   personne ») et l'endroit où ranger votre dossier. L'emplacement proposé convient ; pour
   en prendre un autre, cliquez **Choisir…** : la fenêtre de votre ordinateur s'ouvre (si
   vous ne la voyez pas, elle est derrière le navigateur). Choisir un dossier qui contient
   déjà d'autres fichiers (Documents, par exemple) y crée un dossier « CONCLAVE ».
   Cliquez **Continuer** : il enregistre, et passe à l'étape suivante.
2. **Votre machine** — ce que CONCLAVE a lu de votre ordinateur, et ce qu'il propose. Si
   votre ordinateur peut faire tourner un modèle d'IA : installez Ollama (le lien est là),
   cliquez « Lire à nouveau », puis **Télécharger** le modèle. CONCLAVE dit d'abord sa
   taille (plusieurs Go) : gardez l'ordinateur allumé et CONCLAVE ouvert pendant le
   téléchargement. Puis **Appliquer la formule**.
   <!-- Capture à faire. -->
3. **Votre fournisseur d'IA** — choisissez-en un : CONCLAVE dit en une phrase ce que chacun
   coûte. Mammouth est en français, avec un abonnement à partir de 12 € par mois.
   Cliquez **Créer un compte** : la page du fournisseur s'ouvre ; créez votre compte, puis
   une **clé** (une longue suite de lettres et de chiffres). Copiez-la, revenez dans
   CONCLAVE, cliquez **Saisir la clé**, collez-la, puis **Enregistrer et vérifier**.
   Chez Mammouth, quand CONCLAVE dit **Prête**, c'est fait. Chez un autre fournisseur,
   CONCLAVE dit d'abord « Clé reconnue » : les experts sont encore réglés pour Mammouth.
   - Chez **OpenRouter**, cliquez **Confier le conseil à OpenRouter** sous lui, puis
     **Vérifier** : c'est fait quand CONCLAVE dit **Prête**.
   - Chez **Requesty** ou **Eden AI**, il faut choisir vous-même le modèle de chaque expert :
     cliquez **Finir plus tard, dans Réglages** ; dans l'onglet Réglages, section « Qui
     fait quoi », choisissez un modèle de ce fournisseur pour chaque ligne qui dit « Aucune
     clé Mammouth » ; puis, section Fournisseurs, cliquez **Vérifier** jusqu'à **Prête**.
     Si c'est difficile, demandez à la personne qui vous aide.

   Si votre ordinateur ne fait pas tourner de modèle (ou si Ollama n'y est pas installé),
   un bouton apparaît en bas de l'étape dès que votre clé répond : **Confier l'entretien
   et la lecture à** votre fournisseur. Cliquez-le : CONCLAVE vous dit ce qui sortira de
   votre ordinateur, puis **Confirmer**. Sans cela, l'entretien ne pourrait pas répondre :
   CONCLAVE vous le signale en rouge à la dernière étape.
   <!-- Capture à faire. -->
4. **Votre budget** — facultatif : un montant par mois. CONCLAVE vous prévient à 80 % et
   vous demande avant de le dépasser.
5. **Votre téléphone** — facultatif, voir la partie 6.
6. **Les limites** — trois choses à savoir : l'ordinateur doit être allumé et CONCLAVE
   ouvert pour que le téléphone réponde ; ce qui sort de votre ordinateur, fonction par
   fonction ; ce que coûte un conclave.

**Votre clé est un secret** : elle donne accès à votre compte chez le fournisseur.
CONCLAVE la garde sur votre ordinateur et n'en montre jamais que les quatre derniers
caractères. Ne l'envoyez à personne, pas même à la personne qui vous aide.

## 6. Relier votre téléphone (facultatif)

Pour noter une dépense ou photographier un document depuis votre téléphone, CONCLAVE
utilise **Tailscale**, un réseau privé gratuit qui ne relie que vos appareils.

1. Installez Tailscale sur l'ordinateur (le lien est dans CONCLAVE, onglet Réglages,
   section Téléphone), ouvrez-le et connectez-vous (avec un compte Google, Apple ou
   Microsoft).
2. Installez Tailscale sur le téléphone (App Store ou Google Play), et connectez-vous
   **avec le même compte**.
3. Dans CONCLAVE, cliquez **Publier l'adresse**. CONCLAVE vous dit avant ce que cela
   change : le nom de votre ordinateur sur Tailscale devient public (pas son contenu).
   Si Tailscale demande d'activer HTTPS, CONCLAVE montre le lien : suivez-le, activez, et
   revenez publier.
4. Scannez le **QR code** avec l'appareil photo du téléphone. La page s'ouvre. Sur iPhone,
   dans Safari : Partager, puis « Sur l'écran d'accueil » ; sur Android, dans Chrome : le
   menu ⋮, puis « Ajouter à l'écran d'accueil ».

Le téléphone ne parle qu'à votre ordinateur : ordinateur éteint ou CONCLAVE fermé, il garde
ce que vous notez et l'envoie plus tard.

**Être prévenu quand un conclave est fini.** Un conclave dure plusieurs minutes. Sur le
téléphone, ouvrez CONCLAVE **depuis l'écran d'accueil**, onglet **Synthèse**, puis
**Activer les notifications**, et acceptez la question du téléphone. Une notification
d'essai arrive aussitôt ; ensuite, vous êtes prévenu quand un compte rendu est prêt. La
notification part de votre ordinateur et passe, chiffrée, par le service de notifications
de votre téléphone (Apple ou Google) ; elle ne dit rien de votre dossier. Sur iPhone, cela
ne marche que depuis l'icône de l'écran d'accueil, pas depuis Safari. Pour arrêter :
**Ne plus me prévenir**, au même endroit.

## 7. Au quotidien

- **Ouvrir CONCLAVE** : double-cliquez sur son icône. S'il est déjà ouvert, la page se
  rouvre simplement.
- **Arrêter CONCLAVE** : onglet **Réglages**, section CONCLAVE, **Quitter CONCLAVE**.
  Fermer l'onglet du navigateur ne l'arrête pas : il continue, prêt pour votre téléphone.
- **Si une alerte rouge s'affiche en haut d'un écran** (« Ollama ne répond pas… », « Aucune
  clé… ») : la fonction de cet écran ne peut pas répondre tant que ce n'est pas réglé.
  Cliquez **Régler dans Réglages**, qui vous y mène.
- **Dépenser moins par conclave** : onglet **Réglages**, section « Qui fait quoi », **La
  formule du conseil**. Trois conseils tout faits, avec leur coût estimé pour un conclave :
  **Économique** (un centime ou deux), **Équilibrée**, **Maximale** (le conseil livré, près
  d'un euro). Ce sont les mêmes éditeurs, avec des modèles plus ou moins grands : les avis
  de l'économique sont plus courts et moins fouillés. **Choisir cette formule** change tout
  le conseil d'un coup ; vous pouvez en changer quand vous voulez.
- **Un fournisseur qui n'est pas dans la liste** : onglet **Réglages**, section
  Fournisseurs, **Ajouter un fournisseur**. Collez le lien de son site et cliquez
  **Chercher** : CONCLAVE dit d'abord ce que la recherche coûtera au plus (de un à
  quarante centimes, selon le modèle de votre chef d'orchestre), lit quelques pages
  publiques du site, puis montre une fiche où chaque point est
  marqué « vérifié », « à vérifier » ou « introuvable ». Regardez surtout l'**adresse de
  l'API** : c'est là que partira votre clé. **Ajouter ce fournisseur**, puis saisissez sa
  clé comme pour les autres. Il se retire de la même façon : **Retirer ce fournisseur**.
- **Dicter plutôt qu'écrire** : sous chaque champ où vous écrivez aux experts, le bouton
  **Dicter** écrit ce que vous dites. La première fois, CONCLAVE dit à qui votre navigateur
  confie votre voix pour la changer en texte (Google pour Chrome, Microsoft pour Edge, Apple
  pour Safari), et le navigateur demande l'accès au micro. Rien ne part vers les experts
  avant que vous ne l'envoyiez. Avec Firefox, qui ne sait pas dicter, utilisez la dictée de
  l'ordinateur : sur PC, Windows + H ; sur Mac, la touche 🎤 ou deux fois Fn.
- **Le petit son** : une réponse peut mettre plusieurs minutes. Un son vous prévient quand
  elle arrive, si la page de CONCLAVE est restée ouverte (avec Safari, il peut falloir
  qu'elle reste visible à l'écran).
  Pour le couper : onglet **Réglages**, section **Vous**, décochez « Un petit son quand une
  réponse arrive ». **Écouter** le fait entendre.
- **Une nouvelle version** : à son lancement, CONCLAVE regarde si une version plus récente
  existe. Si oui, **Mise à jour disponible** s'affiche sous les onglets : cliquez dessus,
  puis **Télécharger la version…**. Il ne l'installe pas tout seul : le fichier arrive dans
  Téléchargements (prenez le plus récent s'il en reste un ancien). **Avant de l'installer, quittez CONCLAVE**
  (onglet Réglages, section CONCLAVE, **Quitter CONCLAVE**), sur Mac comme sur PC : sur Mac,
  sans cela, l'ancienne version continuerait de tourner à la place de la nouvelle ; sur PC,
  l'installateur le fermerait de toute façon, après vous l'avoir demandé. Puis installez-la
  par-dessus l'ancienne (sur Mac, acceptez de remplacer CONCLAVE dans Applications ; macOS
  peut redemander « Ouvrir quand même », partie 3). Vos réglages et votre dossier restent.

## 8. En cas de souci

Cliquez **Envoyer un rapport** (en haut de l'onglet Réglages, en bas de chaque page, ou sous
un message d'erreur). CONCLAVE enregistre le rapport dans votre dossier **Téléchargements**
(un fichier `conclave-rapport-….txt`) et ouvre votre messagerie : joignez-y ce fichier (le
trombone), dites en deux mots ce qui s'est passé, et envoyez-le à la personne qui vous aide.
Si la messagerie ne s'ouvre pas, envoyez ce fichier comme vous le feriez d'une photo.

Le rapport dit la version, votre système, les fournisseurs connectés, les dernières erreurs
et le journal de ce que CONCLAVE a fait (les demandes, les appels aux modèles, chaque
erreur et sa cause). Il ne contient **ni votre clé, ni le contenu de vos fiches, ni vos
questions ou les réponses, ni le nom de vos fichiers, ni aucun montant** : ils y sont
masqués. Vous pouvez l'ouvrir pour le lire avant de l'envoyer.

Si CONCLAVE ne s'ouvre pas du tout, une fenêtre le dit, avec le nom d'un fichier
(`journal-du-serveur.txt`) : envoyez ce fichier. Il est dans un dossier que votre
ordinateur cache d'habitude ; pour l'ouvrir :

- **sur Mac** : dans le Finder, menu **Aller**, puis **Aller au dossier…** ; collez
  `~/Library/Application Support/CONCLAVE` et appuyez sur Entrée ;
- **sur PC** : ouvrez l'Explorateur de fichiers, cliquez dans la barre d'adresse en haut,
  collez `%APPDATA%\CONCLAVE` et appuyez sur Entrée.

Le fichier `journal-du-serveur.txt` est là : joignez-le à votre message.

---

## Pour la personne qui aide : quoi vérifier sur un nouvel ordinateur

- L'assistant s'est ouvert, et chaque étape dit « Fait » ou ce qui reste.
- « Votre machine » dit la bonne mémoire, et la bonne formule (un Mac de 8 Go reçoit une
  formule distante ; un PC avec une carte NVIDIA de 8 Go, `qwen3:8b`, jamais mesuré).
- Sous Windows : une pièce photographiée se lit (la reconnaissance de texte de Windows lit
  le français s'il est installé) ; un PDF se lit.
- Le téléphone ouvre la page par le QR code, avec un cadenas dans la barre d'adresse.
- Depuis l'écran d'accueil du téléphone, « Activer les notifications » fait arriver la
  notification d'essai ; Réglages, section Téléphone, dit alors « 1 téléphone sera prévenu ».
- Sans Ollama : l'écran de l'entretien montre l'alerte rouge, et l'assistant propose de
  confier l'entretien au fournisseur.
- « Quitter CONCLAVE » l'arrête, et un double-clic le rouvre.
- Le diagnostic copié ne contient rien de ce qui est promis.
- Depuis le code, `python -m conclave.application --verifier` contrôle une installation
  sans rien servir.
