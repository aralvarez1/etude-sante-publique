# Étude de santé publique — Python + données FAO

Analyse de données alimentaires mondiales (FAO) pour éclairer les enjeux
de santé publique liés à l'alimentation.

---

## Contexte / besoin métier

Dans le cadre d'une mission pour l'OMS, analyse de la disponibilité alimentaire
mondiale pour identifier les zones de pénurie et les déséquilibres nutritionnels.

## Données

- **Source** : Food and Agriculture Organization (FAO) — données mondiales
- **Variables** : disponibilité alimentaire, production, importations, exportations
- **Qualité** : données officielles mais incomplètes pour certains pays
- **Limites** : données agrégées par pays, pas de granularité régionale

## Démarche

1. **Import et nettoyage** des données FAO (gestion des NaN, harmonisation)
2. **Calculs dérivés** : disponibilité en kcal/personne/jour, ratio animaux/végétaux
3. **Analyses** : répartition par pays, par produit, par continent
4. **Visualisations** : cartes, graphiques de répartition, comparaisons
5. **Interprétation** : identification des zones de vulnérabilité alimentaire

## Résultats

- Cartographie de la disponibilité alimentaire mondiale
- Mise en évidence des écarts entre pays et continents
- Estimation de la part de l'alimentation animale vs végétale

## Limites & pistes

- Données agrégées, pas de détail régional
- Pas de prise en compte des pertes et gaspillages
- **Pistes** : croiser avec des données de santé (obésité, malnutrition),
  analyser l'évolution temporelle, modéliser l'impact démographique
