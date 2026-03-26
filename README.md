# videgrenier

## Historique des étapes de développement

1. Initialisation du projet
   - Création de `index.html` et `style.css`
   - Design du poster avec fond `#c8652c` et bloc `.poster` centré en blanc

2. Styles CSS
   - `.poster` : max-width 600px, bordure 2px, coins arrondis, ombre portée
   - `text-transform: uppercase` sur le contenu
   - `.presentation` : taille 2em, letter-spacing 0.1em, font-weight 600
   - `.title` : font `Antonio-Bold`, couleur `#26815c`, font-size 8em, contour noir via `-webkit-text-stroke`
   - `.details` : font `NF-Lepetitcochon-Regular`, font-size 2em, font-weight bold
   - `.registration` : border 4px solid black et bord arrondi
   - `.location` : position absolute relative à `.registration`, fond vert #26815c, texte blanc bold, font `Montserrat-Bold`
   - `.registration` : font `Antonio-Regular`
   - `.line` : flex à partir de 500px (logo gauche, date droite)
   - mobile : logo au-dessus

3. RGAA / accessibilité
   - ajout skip link, focus visible (`outline` pour `a:focus`)
   - converti structure sémantique (`h1`, `h2`, `main`, `section`)
   - emojis accessibles avec `aria-label`

4. SEO / social sharing
   - meta tags Open Graph / Twitter / robots / favicon
   - création de `robots.txt` et `sitemap.xml`

5. Déploiement
   - ajout `package.json` avec script `deploy`: `surge . cbb34.surge.sh`

