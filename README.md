# DrugDealer22

Un jeu de gestion économique et de production de drogues dans un environnement textuel/graphique simple.

---

## 🇫🇷 Guide de Jeu (Français)

### 1. Démarrage et Connexion

1.  **Lancez le jeu** : Exécutez le script Python (`DrugDealer22.py`).
2.  **Acceptez l'Avertissement** : Lisez l'avertissement de prévention (Disclaimer) et cliquez sur "Accepter et Continuer".
3.  **Créer un Compte** : Saisissez un pseudo et un mot de passe, puis cliquez sur **Créer**.
4.  **Connexion** : Utilisez votre pseudo et mot de passe pour vous connecter via **Se connecter**.

### 2. L'Interface (Deal Center)

Une fois connecté, vous êtes par défaut au **Deal Center**. L'interface principale est divisée en deux parties :

* **Terminal (Gauche)** : Affiche les messages du système, les succès de production, les erreurs, et les transactions.
* **Panneaux d'Action (Droite)** : Contient les outils de jeu (Production, Vente, Banque, Onglets).

#### 💊 Production

1.  **Vérifiez la Recette** : La zone de texte jaune montre les composants requis pour la drogue sélectionnée.
2.  **Achetez les Composants** : Les composants doivent être achetés via l'onglet **Black Market** (voir plus bas) en utilisant l'argent de votre **Banque**.
3.  **Lancez la Production** : Sélectionnez la **Drogue** et la **Quantité** souhaitée, puis cliquez sur **Lancer**.
    * La production consomme les composants de votre inventaire.
    * Le temps de production est décompté en temps réel (affiché en haut de l'écran).

#### 💰 Vente / Négociation

1.  **Demandez un Prix** : Sélectionnez la drogue et la quantité que vous voulez vendre (doit être dans votre stock personnel, max 50 unités). Cliquez sur **Demander prix**. Une offre apparaît.
2.  **Négociez** :
    * Le bouton "Demander prix" affiche une offre de base (prix de l'unité et total).
    * Utilisez les boutons **-1$** et **+1$** pour ajuster le prix unitaire.
    * **Augmenter le prix** : Augmente votre profit, mais réduit votre **Réputation (Rep)** (affiché entre parenthèses).
    * **Baisser le prix** : Réduit votre profit, mais augmente votre **Réputation (Rep)**.
3.  **Confirmez** : Cliquez sur **Confirmer vente** pour finaliser la transaction et recevoir l'argent.

#### 🏦 Banque

* Utilisez la Banque pour mettre votre argent à l'abri.
* Seuls les fonds de la **Banque** peuvent être utilisés pour acheter au **Black Market**.

### 3. Les Onglets Principaux

| Onglet | Fonction | Note Importante |
| :--- | :--- | :--- |
| **Deal Center** | Production, Vente, Banque (par défaut). | |
| **Stockage** | Apparaît lorsque vous êtes dans un de vos bâtiments. | Permet de déposer/retirer les drogues de l'entrepôt du bâtiment. |
| **Tram** | Permet de voyager vers vos bâtiments ou le Deal Center. | Le voyage prend 10 secondes. Vous devez attendre. |
| **Bâtiments** | Achat de nouveaux bâtiments pour augmenter votre capacité de stockage. | L'achat utilise votre **Argent** (Money). |
| **Black Market**| Achat des composants nécessaires à la production. | Nécessite des fonds sur votre compte **Banque** (Bank). |

### 4. Commandes et Sauvegarde

* Le jeu **sauvegarde automatiquement** toutes les 10 secondes.
* Vous pouvez entrer des commandes rapides dans la case sous la Banque :
    * `sauvegarder` (ou `save`) : Sauvegarde manuelle.
    * `etat` (ou `status`) : Affiche l'état détaillé de votre inventaire et de vos finances dans le terminal.
    * `confirmer` (ou `confirm`) : Confirme la vente en cours (raccourci).
* Cliquez sur **Quitter (sauvegarde)** pour fermer le jeu proprement.

---
---

## 🇬🇧 Game Guide (English)

### 1. Starting Up and Login

1.  **Start the Game**: Execute the Python script (`DrugDealer22.py`).
2.  **Accept the Disclaimer**: Read the prevention warning (Disclaimer) and click "Accept and Continue".
3.  **Create an Account**: Enter a username and password, then click **Create**.
4.  **Login**: Use your username and password to log in via **Login**.

### 2. The Interface (Deal Center)

Once logged in, you are by default at the **Deal Center**. The main interface is divided into two parts:

* **Terminal (Left)**: Displays system messages, production success, errors, and transactions.
* **Action Panels (Right)**: Contains the game tools (Production, Sale, Bank, Tabs).

#### 💊 Production

1.  **Check the Recipe**: The yellow text area shows the required components for the selected drug.
2.  **Buy Components**: Components must be purchased via the **Black Market** tab (see below) using money from your **Bank** account.
3.  **Start Production**: Select the **Drug** and desired **Quantity**, then click **Start**.
    * Production consumes components from your inventory.
    * Production time is counted in real-time (displayed at the top of the screen).

#### 💰 Sale / Negotiation

1.  **Request Price**: Select the drug and quantity you wish to sell (must be in your personal stock, max 50 units). Click **Request price**. An offer will appear.
2.  **Negotiate**:
    * The "Request price" button displays a base offer (unit price and total).
    * Use the **-1$** and **+1$** buttons to adjust the unit price.
    * **Increasing the price**: Increases your profit, but lowers your **Reputation (Rep)** (shown in parentheses).
    * **Lowering the price**: Lowers your profit, but increases your **Reputation (Rep)**.
3.  **Confirm**: Click **Confirm Sale** to finalize the transaction and receive the money.

#### 🏦 Bank

* Use the Bank to keep your money safe.
* Only funds in the **Bank** can be used for **Black Market** purchases.

### 3. Main Tabs

| Tab | Function | Important Note |
| :--- | :--- | :--- |
| **Deal Center** | Production, Sale, Bank (default). | |
| **Storage** | Appears when you are inside one of your buildings. | Allows you to deposit/withdraw drugs to/from the building's storage. |
| **Tram** | Allows you to travel to your buildings or the Deal Center. | Travel takes 10 seconds. You must wait. |
| **Buildings** | Purchase new buildings to increase your storage capacity. | Purchase uses your **Money** (cash). |
| **Black Market**| Purchase the components needed for production. | Requires funds in your **Bank** account. |

### 4. Commands and Saving

* The game **autosaves** every 10 seconds.
* You can enter quick commands in the entry box below the Bank:
    * `save` (or `sauvegarder`): Manual save.
    * `status` (or `etat`): Displays the detailed status of your inventory and finances in the terminal.
    * `confirm` (or `confirmer`): Confirms the current sale (shortcut).
* Click **Quit (save)** to close the game properly.
