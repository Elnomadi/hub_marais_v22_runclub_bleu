HOKA Formation Hub — V22 (V21 + affiche Run Club peinte + bleu HOKA)
=====================================================================

Ce que V22 ajoute à la V21 (identique au canvas Claude Design)
--------------------------------------------------------------
1. AFFICHE RUN CLUB PEINTE DANS L'IMAGE (jour + nuit)
   store-day.jpg / store-night.jpg contiennent la nouvelle affiche :
   RUN CLUB · CHAQUE MERCREDI & SAMEDI · 1 runner · 9H · LE MARAIS,
   en police HOKA, avec l'éclairage d'origine. Aucun overlay HTML.
   La pastille F passe en badge sur le coin haut-droit de l'affiche
   (à son ancienne place elle se collait au "N" de RUN).

2. BLEU HOKA #009DFF SUR LA CARTE EMEA (jour + nuit)
   - Traits de côte en #009DFF (dans emea-day.svg / emea-night.svg)
   - Halo des pastilles, ombre du ruban "HUB", étiquettes ENTER /
     3D VISIT en #009DFF (texte encre pour rester lisible)
   - Inchangé : l'ombre terracotta du bouton "Enter store" au survol

---------------------------------------------------------------------

HOKA Formation Hub — V21 (base V19 + floor propre + carte premium)
==================================================================

Base : V19 (l'affichage que tu valides : topbar TRAINING HUB / LE MARAIS,
drawer éditorial, cartes mobile, reader, 17 chapitres Gamme Route).
Seuls le floor 3D et la carte EMEA ont changé.

1. FLOOR 3D — image propre + vraies pastilles
   Avant (V19) : store-day.jpg et store-night.jpg étaient des captures du
   canvas avec les pastilles A–G et le bandeau "B Mur ROAD" imprimés DANS
   l'image. Les boutons cliquables étaient invisibles par-dessus, décalés
   de 1 à 2 %, et la lettre C (zone supprimée en V17) restait visible.
   Plus l'overlay Run Club à 3 bonhommes collé sur l'affiche.

   Maintenant :
   - assets/store-day.jpg  = l'illustration d'origine propre (celle de ton
     export Main.dc.html), 3200×1800, sans aucune pastille.
   - assets/store-night.jpg = sa version nuit d'origine, même format.
   - Pastilles A B D E F G = de vrais éléments HTML, même look que
     l'artboard Main du canvas (disque volt, contour encre, lettre HOKA,
     ombre portée, halo qui pulse). Placées exactement au centre des
     positions du canvas. Leur taille suit la largeur de l'image.
   - Zone tactile ≥ 44 px autour de chaque pastille (confort iPhone/iPad).
   - Pastilles hors-rôle : disque crème + lettre grisée (lisible, pas de
     transparence qui bave sur le décor).
   - Overlay Run Club supprimé : l'affiche d'origine reste telle quelle.
   - Plus de lettre C.

2. CARTE EMEA — palette premium V20 réappliquée
   Les 5 changements exacts de la V20 (palette ivoire / encre / bleu
   pacific / terracotta, ruban "HUB" encre avec ombre terracotta, pastilles
   encre avec halo bleu, étiquette "visite" bleue, bouton "Entrer" encre).
   Plus aucun jaune sur la carte.
   + Correctif nuit : les pastilles de la carte sont maintenant des disques
     crème bien lisibles sur fond sombre (une règle en trop les rendait
     sombres sur sombre en V20).

Ce qui n'a pas bougé
--------------------
- Tout le reste de l'interface V19, les rôles, le reader, les contenus.
- Placeholders Supabase (__YOUR_SUPABASE_URL__ / __YOUR_SUPABASE_ANON_KEY__).

Tester en local
---------------
  python3 -m http.server 8080
  → http://localhost:8080
