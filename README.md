# 6AM IN BEIRUT - Reservation Management System

Une application web complète pour gérer les réservations de tables pour la soirée **6AM IN BEIRUT** à Faraya, Kfardebian.

## ✨ Caractéristiques

- 📊 **Floor Plan visuel** avec 128 tables réparties en 12 sections de couleurs
- ➕ **Gestion des réservations** en temps réel
- 📱 **Responsive design** - Fonctionne sur téléphone, tablette et ordinateur
- 💾 **Synchronisation automatique** - Les données se sauvegardent dans le navigateur
- 🔍 **Requêtes intelligentes** - "Combien de tables rouges ?" ou "Tables d'Ahmed ?"
- 🎨 **Dark mode** - Support du mode sombre automatique

## 🚀 Utilisation

1. Ouvrez https://younisexx.github.io/6am-beirut-reservations
2. Utilisez les onglets pour naviguer:
   - **📊 Floor Plan** : Visualisez toutes les tables
   - **➕ New Reservation** : Ajoutez une nouvelle réservation
   - **📋 All Reservations** : Consultez la liste complète
   - **🔍 Query** : Posez des questions sur les réservations

## 📋 Sections de Tables

### Front Stage (90 tables)
- BLUE: 4 tables
- CYAN: 4 tables
- GREEN: 12 tables
- PINK: 14 tables
- YELLOW: 14 tables
- GREY: 16 tables
- RED: 14 tables
- BURGUNDY: 12 tables

### Back Stage (38 tables)
- BLACK: 6 tables
- NAVY: 4 tables
- TURQUOISE: 11 tables
- ORANGE: 15 tables
- GREEN: 2 tables

## 📝 Ajouter une Réservation

1. Cliquez sur **➕ New Reservation**
2. Remplissez les informations:
   - **Name/Promoter**: Nom du promoteur
   - **Number of Guests**: Nombre de personnes
   - **Phone Number**: Numéro de téléphone
   - **Preferred Section**: Sélectionnez la section de couleur
   - **Age Range**: (Optionnel) Tranche d'âge
3. Cliquez **✓ Confirm Reservation**

## 🔍 Faire une Requête

Exemples de requêtes:
- "Combien de tables rouges ?"
- "How many BURGUNDY tables?"
- "Ahmed tables?" (pour voir toutes les tables du promoteur Ahmed)
- "Combien de tables disponibles ?"

## 💾 Données

Les réservations sont automatiquement sauvegardées dans le **localStorage** de votre navigateur. 
Cela signifie:
- ✅ Les données persistent même après fermer l'onglet
- ✅ Accessible de n'importe quel appareil via le même lien
- ✅ Synchronisé automatiquement entre appareils

## 🌐 Accès depuis n'importe où

Partagez ce lien avec vos promoteurs:
```
https://younisexx.github.io/6am-beirut-reservations
```

## 📊 Statistiques en Temps Réel

Le dashboard affiche automatiquement:
- Nombre total de tables
- Tables réservées
- Tables disponibles
- Taux d'occupation en %

## 🛠️ Technique

- **HTML5 + CSS3 + JavaScript vanilla**
- **LocalStorage** pour la persistance des données
- **Responsive Grid Layout** pour le floor plan
- **Dark mode** supporté automatiquement
- **Zéro dépendances externes**

## 📱 Compatibilité

- ✅ Chrome, Firefox, Safari, Edge
- ✅ iPhone, Android
- ✅ Tablettes
- ✅ Mode hors-ligne (après première visite)

## 🎨 Personnalisation

Pour ajouter ou modifier des sections, éditez la section `sections` dans le code JavaScript:

```javascript
const sections = {
    'FRONT': {
        'BLUE': 4,
        'CYAN': 4,
        // ... etc
    },
    'BACK': {
        'BLACK': 6,
        // ... etc
    }
};
```

## ⚙️ Configuration

Les couleurs sont définies dans l'objet `colors`:

```javascript
const colors = {
    'BLACK': '#1a1a1a',
    'NAVY': '#001f5c',
    // ... etc
};
```

## 🆘 Support

Pour toute question ou amélioration, consultez le fichier `index.html` et modifiez directement le code.

## 📜 Licence

Libre d'utilisation pour la soirée 6AM IN BEIRUT.

---

**Développé pour 6AM IN BEIRUT** 🎉
