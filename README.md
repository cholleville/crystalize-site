# crystalizestudio.com

Le site de Crystalize Studio. Cinq pages statiques, aucune dépendance, aucun
outil de construction : ce que contient ce dépôt est exactement ce qui est
servi.

```
index.html                              le studio
assets/site.css                         la feuille commune
synaptika/index.html                    l'application
synaptika/confidentialite/index.html    obligatoire — Play Console
synaptika/suppression-compte/index.html obligatoire — Play Console
synaptika/conditions/index.html         conditions d'utilisation
CNAME                                   crystalizestudio.com
.nojekyll                               sert les fichiers tels quels
```

## Pourquoi ces pages existent

Les deux marquées « obligatoire » ne sont pas décoratives : sans une URL
publique de politique de confidentialité et une page de suppression de compte
accessible **sans installer l'application**, le Play Console refuse la
publication. C'est la raison d'être de ce dépôt.

## Mise en ligne

GitHub Pages, branche `main`, dossier racine. Le fichier `CNAME` fait le reste
une fois le DNS en place.

## Ce qui reste à compléter

- Le **numéro d'entreprise** dans les conditions, le jour de l'inscription à la
  BCE. Voir `docs/conditions-vente-a-activer.md` dans le dépôt de Synaptika :
  les clauses de vente y attendent, hors ligne, tant qu'il n'y a rien à vendre.
- L'**adresse postale** dans la politique de confidentialité, si elle doit y
  figurer.
- Des **captures d'écran** de l'application sur la page Synaptika.
