# Segmentation des Images de la Microscopie Électronique

## Architecture du modèle

Notre modèle est basé sur l'architecture `UNET` et se structure de la façon suivante:

![Architecture UNET](resources/u-net-architecture.png)

Ce qui nous donne l'architecture suivante avec `Tensorflow` et python.

![Architecture Model](resources/architect_model.png)

---

## Courbes de performances

Nous avons représenté deux métriques pour notre modèle, `accuracy` et `loss`.

- Courbe pour l'accuracy:

![Courbe Accuracy](resources/accuracy.png)

- Courbe pour le loss:

![Courbe Loss](resources/loss.png)

---

## Résultats

Le modèle est plutôt précis, voici quelques exemples sur des images de test:

- Image initiale

![test 1](data/membrane/test/1.png)

- Prédiction du modèle

![test 1 prédiction](data/membrane/test/1_predict.png)

Autre exemple avec une autre image.

- Image initiale

![test 6](data/membrane/test/6.png)

- Prédiction du modèle

![test 6 prédiction](data/membrane/test/6_predict.png)

