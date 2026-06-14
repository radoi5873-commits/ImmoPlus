# 🇧🇯 Bénin Prestige Immobilier

Une plateforme web haut de gamme et responsive dédiée au marché immobilier de luxe au Bénin. Ce portail interactif permet aux clients de rechercher des propriétés hautement sécurisées, d'estimer la valeur de leurs biens et d'interagir facilement avec des agents immobiliers professionnels.

---

## 🌟 Fonctionnalités Clés

### 👤 Espace Client (Découvrir & Estimer)
* **Recherche & Filtres Avancés :** Filtrez les biens par offre (Achat, Location), type de bien, budget et caractéristiques clés du marché béninois (Titre Foncier obligatoire 🔒, Présence de piscine 🏊, Vue sur Mer 🌊).
* **Simulateur d'Estimation :** Évaluez en quelques secondes la fourchette de valeur de votre bien (vente ou loyer) selon des critères et coefficients locaux précis (Haie Vive, Fidjrossè, Cadjehoun, Calavi, Ouidah, etc.).
* **Intégration WhatsApp Pro :** Bouton de chat flottant et partage instantané des résultats de l'estimation par message WhatsApp pré-rempli.
* **Simulateur de Prêt & Guide d'Achat :** Outils d'aide à la décision pour orienter les acheteurs sur les aspects légaux du foncier au Bénin.
* **Système de Favoris :** Enregistrez vos biens favoris d'une session à l'autre grâce à la persistance locale (`localStorage`).

### 💼 Espace Professionnel (Console Agent)
* **Accès Sécurisé :** Authentification sécurisée par code PIN (Code d'accès par défaut : **`229`**).
* **Tableau de Bord Premium :** Cartes de statistiques professionnelles mises à jour en temps réel (Total des annonces, valeur estimée cumulée du portfolio, nombre de prospects qualifiés).
* **Gestion du Catalogue :** Formulaire complet d'ajout de nouvelles annonces (avec prise en charge des documents légaux comme le Titre Foncier) et suppression sécurisée.
* **Export de Données :** Exportez la boîte de réception des prospects/leads en un clic au format **CSV** pour intégration CRM ou Excel.
* **Modaux Personnalisés Asynchrones :** Remplacement des fenêtres d'alerte et de confirmation système par des fenêtres modales intégrées au design de la plateforme pour une fluidité absolue.

---

## 🛠️ Stack Technique

* **Structure & UI :** HTML5 Sémantique, CSS (Vanilla CSS & Tailwind CSS CDN).
* **Icônes :** Lucide Icons.
* **Logique Applicative :** Vanilla JavaScript (architecture Single-Page Application).
* **Persistance des Données :** `localStorage` du navigateur.

---

## 🚀 Démarrage Rapide

1. Clonez ou téléchargez les fichiers de ce projet.
2. Ouvrez le fichier `index.html` directement dans votre navigateur ou lancez un serveur de développement local :
   ```bash
   # Avec Python
   python3 -m http.server 8000
   ```
3. Ouvrez [http://localhost:8000](http://localhost:8000) dans votre navigateur.

---

## 📄 Licence

Ce projet est sous licence **MIT**. Voir le fichier [LICENSE](./LICENSE) pour plus de détails.
