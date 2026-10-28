# BAKUON · Notes de version

## 2.4 · 28 octobre 2026 · Plus grand, plus beau, plus vivant

- **Combiné agrandi.** Le compte-tours prend toute la hauteur et les six manos sont bien plus gros (environ 60 % au format de la Tesla). Ils sont disposés en arc autour du compte-tours.
- **Nouveau combiné USA.** Cadrans crème à chiffres noirs dans des cuvettes chromées, aiguilles rouges, panneau en aluminium bouchonné, bandeau en cuir surpiqué et gros voyant de passage de rapport. Il ne ressemble plus du tout à EURO.
- **EURO plus lumineux.** Cadrans anthracite éclairés, chiffres blancs plus grands, zone rouge lumineuse, panneau en carbone verni, décor de col alpin au soleil couchant.
- **MONO refait.** Un vrai volant : corps en carbone, poignées caoutchouc, molettes TC, BB, ENG et DIFF, écran central en couleurs, petits écrans pour les manos, et un décor de circuit au crépuscule.
- **Commandes à gauche.** START, les modes, les pédales et le panneau GPS sont maintenant du côté du conducteur, le garage passe à droite. Sur téléphone, les commandes passent au-dessus du garage.
- **Mode Route moins extrême.** Les rapports tiennent le moteur dans une plage de croisière. Pour un moteur qui monte à 8 000 tr/min, Caractère au milieu : de 2 500 à 3 500 tr/min en ville, de 3 000 à 4 000 sur route, et jusqu'à environ 5 800 sur une accélération franche. Plus d'allers-retours entre deux rapports.
- **Caractère bien plus marqué.** Sage passe tôt et reste calme. Spectacle monte près du rupteur, rétrograde fort et fait claquer l'échappement. Le réglage par défaut est au milieu.
- **Monoplaces : vrais passages de course.** Montée de rapport avec une coupure d'allumage brève, gros coup de gaz automatique à chaque rétrogradage avec crépitement, claquement de boîte séquentielle, et rafale de rétrogradages au freinage (de 6e en 1re en moins de 2 secondes).
- **Des moteurs plus différents.** Chaque son est retravaillé d'après les particularités réelles du moteur, et vérifié par mesure pour que deux moteurs d'une même page ne se ressemblent plus :
  - le V10 culbuté a son allumage irrégulier « de camion » ;
  - le 5 cylindres a son glouglou ;
  - le rotatif est plus rauque ;
  - le Turbo rallye est plus grave et plus rugueux que le Turbo drift, plus aigu et plus nerveux ;
  - le Biturbo 4x4 est plus métallique que le Biturbo séquentiel, plus rond et plus grave ;
  - le V8 double arbre est plus lisse et plus aigu que le V8 culbuté ;
  - le V12 de GT est plus soyeux, le V10 de supercar plus hurleur ;
  - l'Atmo 9 000 tours a son sifflement de distribution.

## 2.3 · 28 octobre 2026 · Le même écran dans les trois modes

- Un bandeau orange « Prudence » reste affiché en haut, dans tous les modes : ne rien régler en roulant, garder un volume qui laisse entendre la route, et le son suit le GPS avec un peu de retard.
- Le combiné prend toute la première ligne : le compte-tours au centre, entouré de six manos (pression de turbo, pression et température d'huile, température d'eau, température d'échappement, richesse). Sur téléphone, les manos forment une rangée sous le compte-tours.
- En dessous, le garage en tuiles à gauche et les commandes à droite, dans les trois modes. À droite : les pédales et la boîte en Piste et en Démo, le panneau GPS en Route.
- Les cadres et les boutons gardent exactement la même taille d'un mode à l'autre.
- Le mano de boost s'illumine quand le turbo décharge (jamais en mode Route).
- Les libellés trop longs sont raccourcis.

## 2.2 · 28 octobre 2026 · Un mode Route plus vivant

- Nouveau réglage **Ambiance** pour le mode Route :
  - **Ville** : rapports courts, pour profiter du son à basse vitesse ;
  - **Route** : rapports réels, pour la campagne et l'autoroute ;
  - **Auto** (par défaut) : rapports courts en ville, de plus en plus longs avec la vitesse.
- La boîte suit ta conduite, mesurée par le GPS :
  - en conduite cool, elle passe les rapports tôt ;
  - quand tu pousses, elle les passe plus tard ;
  - sur une accélération franche, elle rétrograde d'un ou deux rapports et monte en surrégime ;
  - quand tu ralentis, elle rétrograde avec coup de gaz et retours de flamme.
- Le curseur Style de conduite devient **Caractère** (de Sage à Spectacle) et dose tout cela.
- La vitesse affichée reste la vraie.
- Chaque moteur a un nom qui dit son caractère (« Biturbo 4x4 », « V8 culbuté », « 6 à plat hurleur »…). Les codes châssis et moteur restent en petit pour les connaisseurs.
- Libellés des pédales plus grands.

## 2.1 · 28 octobre 2026 · Monoplaces, son en WebAssembly et notice

- La page des monoplaces s'appelle désormais **MONO**. Les noms protégés ne sont plus cités : il ne reste que des codes techniques de moteurs et de châssis.
- L'Atelier passe en grands caractères, avec des curseurs adaptés au doigt.
- Sur les pages EURO et USA, la lune se place toujours dans un espace libre de la barre du haut, sans passer derrière un bouton, quelles que soient la langue et la taille de l'écran.
- Les sous-titres des enseignes EURO et USA ne sont plus coupés en anglais.
- Le moteur sonore est compilé en WebAssembly : le son est identique et le calcul deux fois plus rapide.
- Le code du site est protégé. Les sources sont dans un dépôt privé, et la vitrine publique ne contient que le site compilé.
- Nouvelle notice d'utilisation d'une page en PDF, avec un QR code vers le site.

## 2.0 · 27 octobre 2026 · La refonte

- L'application est entièrement réécrite.
- L'interface est dessinée à taille fixe, puis mise à l'échelle de l'écran : rien ne défile. Elle existe en trois formats : plein écran, navigateur de la Tesla à côté de la carte, et téléphone.
- Un avertissement de prudence s'affiche à chaque ouverture et doit être validé avant de démarrer.
- Les réglages sont regroupés dans l'**Atelier**, qui s'ouvre dans une fenêtre au centre. Pour la fermer : la croix, la touche Échap ou un clic à côté.
- Le changement de page est animé.
- Le son des monoplaces est refait, plus chaud et plus rauque.
- GPS : la vitesse est anticipée à partir de l'accélération, ce qui divise par plus de deux l'erreur moyenne.

## 1.1 · 27 octobre 2026 · Quatre pages

- Quatre pages, chacune avec son décor, son enseigne, son compte-tours, ses manos et ses miniatures : JDM (Tokyo au néon), EURO, USA et monoplaces. Le sélecteur de page est à côté de FR/EN.
- 15 nouveaux moteurs, soit 21 au total : V8 à vilebrequin plat ou croisé, 6 à plat, 5 cylindres, V10, V12, compresseur volumétrique, et trois époques de monoplaces (V12 1995, V10 2005, V8 2013).
- Le son est retravaillé pour les haut-parleurs de la Tesla : aigus plus ouverts, grave plus propre, niveau plus fort. Le flutter est plus présent.
- Le mode Route (GPS) est actif d'office.

## 1.0 · 27 octobre 2026 · Première version

- Son moteur synthétisé en direct dans le navigateur, sans aucun enregistrement.
- Six moteurs japonais : RB26, 2JZ, 13B rotatif, F20C, 4G63 et SR20.
- Trois modes : Route (le son suit le GPS), Piste (pédales à l'écran) et Démo (un show de 35 secondes).
- Turbo, flutter ou blow-off, retours de flamme, anti-lag, 2-step, boîte automatique ou manuelle.
- Décor de Tokyo la nuit, combiné avec un compte-tours arc-en-ciel et six manos, interface en français et en anglais.

© 2026 Matthieu Violier. Tous droits réservés.
