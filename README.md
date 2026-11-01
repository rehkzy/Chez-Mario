# Chez Mario — site vitrine

Site une page de la pizzeria Chez Mario (Ivry-sur-Seine). HTML/CSS/JS autonome, sans build.

- `index.html` : la page. Tout ce qui change (adresse, horaires, carte, liens Deliveroo / Uber Eats) est dans le bloc `CONFIG` en haut du `<script>`.
- `photos/` : visuels de la carte (JPEG ≤ 1400 px).
- `logo.svg` : logo source. Dans la page, le logo est inliné en `<symbol>` ; les lettres et la toque prennent la couleur du groupe `.letters`.

Hébergement : Vercel, déployé automatiquement depuis la branche `main` (site statique, aucun build). URL : https://chezmario.vercel.app/
