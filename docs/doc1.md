---
id: doc1
title: Introduction
sidebar_label: Introduction
---

Le but d'un test est de vérifier qu'une fonctionnalité fait ce que l'on attend d'elle.

Les tests d'une application sont une phase très importante dans les cycles de développement et de maintenance d'une application. Ils permettent de détecter des bugs et de s'assurer que l'application réponde au cahier des charges et aux spécifications.

Ces tests peuvent prendre différentes formes :

tests unitaires : les tests unitaires automatisés sont un des mécanismes les plus importants pour améliorer la qualité et tenter de garantir la fiabilité du code d'une application.

tests d'intégration

tests de recette : le but est de vérifier que l'application réponde aux spécifications fonctionnelles. Ces tests sont faits par les utilisateurs qui devraient fournir un procès verbal de recette

tests de charge (robustesse, performance, montée en charge, ...)

tests de stress

tests d'acceptabilité

tests de sécurité
...

Jest est un dhduehudhehdeude
A noter :
Jest est intégré de base avec les applications générées par Create React App. Si on regarde le fichier package.json à la racine du projet, on voit qu’il propose un script test dont la commande est react-scripts test --env=jsdom , lequel utilise Jest en interne.
On trouvait également un fichier src/App.test.js qui contient une suite de test basique, qu’on appelle un smoke test, qui vérifie simplement que notre composant <App/> arrive à réaliser son rendu sans problème.

## Installation

Installer Jest à l'aide de yarn :

```
yarn add --dev jest
```

Installer Jest à l'aide de npm :

```
npm install --save-dev jest
```

## Mauris In Code

```
Mauris vestibulum ullamcorper nibh, ut semper purus pulvinar ut. Donec volutpat orci sit amet mauris malesuada, non pulvinar augue aliquam. Vestibulum ultricies at urna ut suscipit. Morbi iaculis, erat at imperdiet semper, ipsum nulla sodales erat, eget tincidunt justo dui quis justo. Pellentesque dictum bibendum diam at aliquet. Sed pulvinar, dolor quis finibus ornare, eros odio facilisis erat, eu rhoncus nunc dui sed ex. Nunc gravida dui massa, sed ornare arcu tincidunt sit amet. Maecenas efficitur sapien neque, a laoreet libero feugiat ut.
```

## Nulla

Nulla facilisi. Maecenas sodales nec purus eget posuere. Sed sapien quam, pretium a risus in, porttitor dapibus erat. Sed sit amet fringilla ipsum, eget iaculis augue. Integer sollicitudin tortor quis ultricies aliquam. Suspendisse fringilla nunc in tellus cursus, at placerat tellus scelerisque. Sed tempus elit a sollicitudin rhoncus. Nulla facilisi. Morbi nec dolor dolor. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Cras et aliquet lectus. Pellentesque sit amet eros nisi. Quisque ac sapien in sapien congue accumsan. Nullam in posuere ante. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Proin lacinia leo a nibh fringilla pharetra.

## Orci

Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Proin venenatis lectus dui, vel ultrices ante bibendum hendrerit. Aenean egestas feugiat dui id hendrerit. Orci varius natoque penatibus et magnis dis parturient montes, nascetur ridiculus mus. Curabitur in tellus laoreet, eleifend nunc id, viverra leo. Proin vulputate non dolor vel vulputate. Curabitur pretium lobortis felis, sit amet finibus lorem suscipit ut. Sed non mollis risus. Duis sagittis, mi in euismod tincidunt, nunc mauris vestibulum urna, at euismod est elit quis erat. Phasellus accumsan vitae neque eu placerat. In elementum arcu nec tellus imperdiet, eget maximus nulla sodales. Curabitur eu sapien eget nisl sodales fermentum.

## Phasellus

Phasellus pulvinar ex id commodo imperdiet. Praesent odio nibh, sollicitudin sit amet faucibus id, placerat at metus. Donec vitae eros vitae tortor hendrerit finibus. Interdum et malesuada fames ac ante ipsum primis in faucibus. Quisque vitae purus dolor. Duis suscipit ac nulla et finibus. Phasellus ac sem sed dui dictum gravida. Phasellus eleifend vestibulum facilisis. Integer pharetra nec enim vitae mattis. Duis auctor, lectus quis condimentum bibendum, nunc dolor aliquam massa, id bibendum orci velit quis magna. Ut volutpat nulla nunc, sed interdum magna condimentum non. Sed urna metus, scelerisque vitae consectetur a, feugiat quis magna. Donec dignissim ornare nisl, eget tempor risus malesuada quis.
