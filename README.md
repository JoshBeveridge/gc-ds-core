[La version française suit.](#utilitaire-de-système-de-design-gc)
<br/>
<br/>

# GC Design System Utility

GC Design System Utility is a utility framework for the GC Design System core. It is based on functional CSS (also called atomic CSS or utility-first CSS) that favors small, single-purpose classes with names based on their visual function. These classes are easy to understand, reusable and can be used together to build complex layouts.
<br/>
<br/>

## Documentation

You can find the full documentation for GC Design System Utility on [https://design-system.alpha.canada.ca/](https://design-system.alpha.canada.ca/).
<br/>
<br/>

## Installation

### How to install using NPM

- Create a new project or go to the root folder of your existing project.
- Run `npm install @cdssnc/gcds-utility` to install the GC Design System Utility package.

### How to install using CDN

#### Add the code

Use the latest version of GC Design System Utility. Pinned versions provide stability and predictability because the code will remain consistent and won't change unexpectedly, which can be crucial for maintaining the stability of an application. However, it requires manual updating of the CDN links whenever a newer version of GC Design System Utility is released.

Place the following code in the `<head>` element of your site. Replace `<version-number>` with the latest version number to receive corresponding updates.

```
<!-- GC Design System Utility -->
<link rel="stylesheet" href="https://cdn.design-system.alpha.canada.ca/@cdssnc/gcds-utility@<version-number>/dist/gcds-utility.min.css">
```

#### Automatic updates using `@latest`

Use the `@latest` version of GC Design System Utility to receive automatic updates whenever a new version is released. **While it removes the need to manually update the CDN links, it adds the risk of introducing breaking changes to the codebase as new versions are automatically applied**.

<br/>

## Local installation

- Clone the repo `git clone https://github.com/cds-snc/gcds-utility`.
- Run `npm install` to install all Node.js dependencies.
- Run `gulp` to monitor your source files for any changes.
- Run `gulp compile` to compile and minify all CSS files.
  <br/>

## How to contribute

If you are interested in contributing to GC Design System Utility, please read our [contributing guidelines](https://github.com/cds-snc/gcds-utility/blob/main/CONTRIBUTING.md).
<br/>
<br/>

## License

Code released under the [MIT License](https://github.com/cds-snc/gcds-utility/blob/main/LICENSE).
<br/>
<br/>

# --------------------------------------------------------

<br/>
<br/>

# Utilitaire de Système de design GC

L'utilitaire de Système de design GC est un cadre utilitaire pour la base de ce système. Cet utilitaire est fondé sur un code CSS fonctionnel (aussi appelé « atomic CSS » ou encore « utility-first CSS ») qui privilégie de petites classes à but unique nommées selon leur fonction visuelle. Ces classes sont réutilisables et faciles à comprendre. De plus, elles peuvent être combinées pour créer des structures complexes.
<br/>
<br/>

## Documentation

Toute la documentation sur l'utilitaire de Système de design GC est accessible à l'adresse [https://systeme-design.alpha.canada.ca/](https://systeme-design.alpha.canada.ca/).
<br/>
<br/>

## Installation

### Installation à l'aide de NPM

- Créez un nouveau projet ou naviguez vers le dossier racine de votre projet existant.
- Exécutez `npm install @cdssnc/gcds-utility` pour installer le progiciel de l'utilitaire de Système de design GC.

### Installation à l'aide de CDN

#### Ajoutez le code

Utilisez la version la plus récente de Utilitaire de Système de design GC. Les versions épinglées offrent stabilité et prévisibilité parce que le code ne changera pas de manière inattendue, ce qui peut être crucial pour maintenir la stabilité d'une application. Toutefois, il faut mettre à jour manuellement les liens CDN chaque fois qu'une version plus récente de Utilitaire de Système de design GC est publiée.

Insérez le code qui suit à l'intérieur de la balise `<head>` de votre site. Remplacez `<version-number>` par le numéro de version le plus récent pour recevoir les mises à jour correspondantes.

```
<!-- GC Design System Utility -->
<link rel="stylesheet" href="https://cdn.design-system.alpha.canada.ca/@cdssnc/gcds-utility@<version-number>/dist/gcds-utility.min.css">
```

#### Mises à jour automatiques grâce à `@latest`

Utilisez la version `@latest` de Utilitaire de Système de design GC pour recevoir des mises à jour automatiques chaque fois qu'une nouvelle version est publiée. **Bien que cette approche vous évite la mise à jour manuelle des liens CDN, elle court le risque d'introduire des modifications qui entraînent une rupture de compatibilité avec le code base à mesure que les nouvelles versions sont automatiquement appliquées**.

<br/>

## Installation locale

- Copiez le référentiel `git clone https://github.com/cds-snc/gcds-utility`.
- Exécutez ensuite `npm install` pour installer toutes les dépendances Node.js.
- Puis, exécutez `gulp` pour surveiller tout changement survenant dans vos fichiers sources.
- Finalement, exécutez `gulp compile` pour compiler et minifier tous les fichiers CSS.
  <br/>

## Apportez votre contribution

Si vous souhaitez contribuer aux unités de style de Système de design GC, veuillez lire nos [lignes directrices sur la contribution](https://github.com/cds-snc/gcds-utility/blob/main/CONTRIBUTING.md).
<br/>
<br/>

## Licence

Code publié en vertu de la [licence MIT](https://github.com/cds-snc/gcds-utility/blob/main/LICENSE) (en anglais).
<br/>
<br/>
