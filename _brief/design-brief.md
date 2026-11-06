# Baraka Energy 2026 — note de design

**Identité** : Brand-Forward (couleurs du logo) · signature : bandeau blanc avec logo + filet vert, graphiques « vert marque » sur fond clair.
**Palette** : vert #62BB4B (chiffre d'affaires) · marine #021C55 · turquoise #1F8FA8 (panier moyen) · ambre #E8A317 (unités) · ardoise #5B6B8C (agents) · fond de page #F3F6FA.
**Typographie** : Segoe UI / Segoe UI Semibold.

| Page | Archétype | Question posée |
|---|---|---|
| Vue d'ensemble | Executive (bande KPI) | Où en sont les ventes, quand, quoi, comment est-on payé ? |
| Pays et agents | Comparatif | Qui et où vend le plus ? |
| Produits et paiements | Analytique | Quels produits, quels modes de paiement, quel panier ? |

**Navigation** : navigateur de pages dans le bandeau. **Segments** (Mois, Pays, Catégorie) synchronisés sur les 3 pages.
**Modèle** : table `Calendrier` (M, dérivée des dates de vente), 16 mesures DAX (dossiers Ventes, Équipe, Évolution, Classements), `Montant USD` en décimal, paramètre `Chemin du fichier Excel`.
**À savoir** : les titres de page sont des messages fixes valables sur la période complète non filtrée.
