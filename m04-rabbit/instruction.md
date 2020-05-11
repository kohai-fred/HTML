## INSTRUCTIONS
Dégradé, translation, transformation, animation en CSS
ATTENTION : Vous devez travailler en mobile first

Note : Lorsque vous avez la phrase "par défaut", cela veut dire que les propriétés CSS vont s'appliquer sur la balise body

## HTML
Utiliser les balises sémantiques

## CSS
Utiliser le Uppercase pour tous les textes en majuscules

- Positionnement dans l'espace :
    - Utilisation du display: flex

- Les paliers media queries utilisés :
    - mobile (le code css par défaut)
    - Spécial 360px et supérieur
        - A partir de ce palier le logo devra avoir une largeur de 250px. Avant, il aura une largeur de 100%.
    - Spécial 600px et supérieur
        - Palier à partir duquel les liens de la bar de nav du footer sont alignés.
    - Spécial 660px et supérieur
        - Palier à partir duquel le dégradé du header est à 90deg. Avant, il était à 180deg.
    - tablette 768px et supérieur
        - Palier à partir duquel le dégradé du header est à 130deg.
    - desktop 1025px et supérieur

- largeurs du site :
    - Créer une class container qui prendra comme valeur max-width :
        - en mobile : 100%
        - en desktop : 1500px

- Polices utilisées :
    - Les titres et la nav dans le header : QuentinPro (police locale)
    - Le texte par défaut : Open sans (police google fonts)

- Taille de police et comportement :
    - line-height par défaut : 2
    - Taille du texte par défault : 1.6rem
    - Graisse des titres (font-weight) : normal
    - Taille du  h1 : 4rem
    - Taille des h2 : 3rem
    - Taille des h3 : 2.5rem
    - Line height dans la nav du header : 1.5
    - Taille des liens dans la nav du header : 2.5rem
    - Espacement des lettres du mot Rabbit : 5px

- Fontawesome :
    - fa-facebook
    - fa-twitter
    - fa-linkedin
    - Taille : 5rem
    - Largeur et hauteur : 70px
    - Couleur icônes et bordure : #fff
    - Couleur de fond et bordure au survol : #FF9D00
    
- Couleurs :
    - Fond du body #444
    - Couleur Orange : #FF9D00
    - Couleur du dégradé dans le header #fff et #333
    - Couleur de l'ombrage sur le header et le footer rgba(0,0,0,0.2)
    - Couleur du texte dans la nav du header #fff
    - Couleur du texte dans la nav du header au survol : #FF9D00
    - Couleur des bordure sur les titres h2 : rgba(0, 0, 0, 0.075)
    - Couleur de la bordure sous les titres des articles : #FF9D00
    - Couleur de fond des liens "En savoir plus" : #FF9D00
    - Couleur de fond des liens "En savoir plus" au survol : #e58a02
    - Couleur du texte des lien "En savoir plus" : #fff

- Effets d'animation :
    - Appliquer une transition de 0.4s sur le sélecteur universel dès la version mobile
    - En desktop uniquement (à partir de 1025px donc) :
        - Le logo Rabbit subit une rotation de 15deg au survol de la souris
        - Les liens de la nav du header subissent une translation vers le bas de 10px au survol de la souris
        - Les articles de la section "Découvrez nos vêtements" subissent un zoom de 1.1 et un ombrage rgba(0,0,0,1) au survol de la souris
        - On applique une animation "effet rebond" d'une durée de 0.35s et d'itération infinie sur les icônes des réseaux sociaux, au survol de la souris

## A rechercher par vous-même
- Trouver comment intégrer une google maps. ATTENTION solution javascript non souhaitée. Uniquement une solution html.