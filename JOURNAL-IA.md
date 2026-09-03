
### Pertinentes ICI 
- Séparation _uiState (privé, mutable) / uiState (exposé, lecture seule) : encapsulation correcte du StateFlow.
- Utilisation de MutableStateFlow : permet à Compose d'observer l'état.
- Utilisation de copy() sur EtatUi immuable : respecte l'immutabilité demandée.
- Utilisation de update() : modification correcte de l'état à partir de sa valeur précédente.
- Centralisation de l'état du panier dans le ViewModel : respecte le flux unidirectionnel.

### Non pertinentes 
- Architecture MVVM plus complète (injection de dépendances, Repository) : ce sont des sujets réels
  et importants dans une vraie application Android, mais ils dépassent l'objectif du Mini-TP, qui se
  limite à la couche d'état avec StateFlow.
- Validation de poidsKg (empêcher une valeur négative) : relève de la logique métier, non de
  l'objectif du TP .
- Routes typées / architecture de navigation avancée : sujet indépendant du ViewModel étudié ici.

