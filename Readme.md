# Layout Paragraph Builder

Ce module permet, avec l'utilisation du Theme **Admin Theme For Layout Paragraph Builder**, un affichage WISIWIG type elementor sur les pages d'ajout et d'édition de node (exemple: page de base, page personnalisée, article, ...)

## Requis

Pour que ce module fonctionne il faut :

 - Installer le thème `Admin Theme For Layout Paragraph Builder`
 - Utiliser le nom machine `field_components` pour le champ référence de paragraphes dans les types de contenu
 - Créer à la racine de votre thème un dossier Admin
 - Ajouter à l’intérieur un fichier `styles.less`
 - Et ajouter ce contenu :

```css
/**
 * Layout Builder
 */

@import  "../css/variables.css";
@import  "../css/fonts.css";
#admin-layout-builder {
	@import (less) "../css/styles.css";
	/* Ajouter vos fichiers styles ici */
}
```

> Attention ! Il faut seulement ajouter les fichiers nécessaires, en plus il ne faut pas laisser des imports de fichier inexistant.
