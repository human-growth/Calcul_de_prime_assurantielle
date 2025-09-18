# Calcul de la prime d’un contrat décès

## Objectif
Tarifer un contrat décès temporaire à partir d’une table de mortalité et de l’actualisation des flux financiers.

## Contenu
- Utilisation d’une table de mortalité (INSEE, HMD).
- Calcul des probabilités conditionnelles de décès/survie.
- Calcul de la prime pure :
 $$
\pi = \sum_{t=1}^{n} \left( v^t \cdot q_{x+t-1} \cdot p_x^{t-1} \cdot C \right)
$$

- Comparaison capital unique vs rente.
- Visualisations : évolution de la prime selon âge, durée, capital, taux d’intérêt.

## Technologies
- Python : pandas, numpy, matplotlib
- Jupyter Notebook pour la documentation

## Résultats attendus
- Calcul automatisé de primes pures pour différents profils.
- Graphiques illustrant l’effet de l’âge et de la durée sur la prime.

## Compétences mises en avant
- Probabilités de survie et de décès
- Mathématiques financières (actualisation)
- Application de l’actuariat vie

## Sources de données
- INSEE : [Tables de mortalité](https://www.insee.fr/fr/statistiques/2414942)  
- Eurostat : [Life tables](https://ec.europa.eu/eurostat/web/population-demography)  

<script type="text/javascript" async
  src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.7/MathJax.js?config=TeX-MML-AM_CHTML">
</script>
