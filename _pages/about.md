---
permalink: /
title: "BIENVENUE"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

بسم الله، والحمد لله، والصلاة والسلام على رسول الله وعلى آله وصحبه ومن اهتدى بهداه
---

<p>
Bonjour ! Je m'appelle Samy Mkhinini. Je suis un étudiant en mathématiques fondamentales ayant comme champ de recherche la théorie algébrique des nombres. Passionné par l'arithmétique, je m'intéresse notamment à l'arithmétique des courbes elliptiques, à la théorie d'Iwasawa, aux systèmes d'Euler, aux fonctions \(L\) \(p\)-adiques, aux déformations des représentations galoisiennes, à la théorie de Hodge \(p\)-adique et au programme de Langlands.
</p>

<p>
Un problème important en théorie des nombres concerne l'étude des groupes de cohomologie des représentations galoisiennes globales, notamment leurs liens avec les valeurs des fonctions \(L\). La théorie des systèmes d'Euler constitue un outil essentiel dans cette étude. Ces derniers consistent en des collections de classes de cohomologie associées à une représentation galoisienne donnée sur des extensions abéliennes du corps de base, et satisfaisant des conditions de compatibilité lorsque le corps varie. L’une des applications les plus puissantes de cette théorie réside dans l’étude des groupes de Selmer, qui seront présentés un peu plus loin sur cette page.
</p>

<p>
Par exemple, un problème auquel je me suis intéressé l'année dernière en M2 est le suivant : étant donnée une courbe elliptique \(E\) définie sur \(\mathbb{Q}\), on peut considérer les courbes lisses, projectives et géométriquement connexes de genre \(1\) dont \(E\) est la jacobienne, autrement dit les torseurs sous \(E\). Si une telle courbe possède des points "locaux", c'est-à-dire dans \(\mathbb{R}\) et dans chaque \(\mathbb{Q}_p\), pour \(p\) premier, possède-t-elle nécessairement un point "global" dans \(\mathbb{Q}\) ? On appelle ce principe : le principe "local-global". Dans le cas des formes quadratiques, la réponse est oui : c'est le théorème de Hasse-Minkowski. En revanche, dans le cas plus sophistiqué des courbes elliptiques, la réponse est : pas toujours. Toutefois, il existe un objet, attaché à une courbe elliptique, qui mesure précisément les obstructions à ce principe local-global pour les torseurs sous \(E\). Ce dernier s'appelle le groupe de Shafarevich-Tate, et est souvent noté \[\textnormal{Ш}(E/\mathbb{Q}).\] Les éléments non triviaux de ce groupe représentent ainsi les torseurs sous \(E\) qui admettent des points dans \(\mathbb{R}\) et dans tous les \(\mathbb{Q}_p\), mais aucun point rationnel sur \(\mathbb{Q}\). Le cardinal de ce même groupe apparaît notamment dans la conjecture BSD, qui prédit ainsi sa finitude (conjecturée par Shafarevich et Tate), et justement, une avancée majeur allant dans ce sens est due à Victor Kolyvagin. En effet, étant donné un corps \(K\) quadratique imaginaire, ce dernier prouva, sous l'hypothèse \(y_K\) d'ordre infini dans \(E(K)\), que le rang de \(E(K)\) est \(1\) et que le groupe \(\textnormal{Ш}(E/K)\) est fini, d'ordre divisant \(t_{E/K}(I_K)^2\), où \(t_{E/K}\) est un entier dont les facteurs premiers dépendent seulement de \(E\) et où \(I_K = [E(K) : \mathbb{Z}y_K]\), avec \(y_K\) la trace d'un point de Heegner. Combiné à la célèbre formule de Gross-Zagier \[L'(E/K,1) = \frac{\textstyle \iint_{E(\mathbb{C})}\omega\wedge\overline{i\omega}}{\sqrt{D}} \cdot \hat{h}(y_K),\] le théorème de Kolyvagin implique un cas particulier de la conjecture BSD. Cette formule de Gross-Zagier dit en substance que \(\textnormal{ord}_{s=1}L(E/K,s) = 1 \) si, et seulement si, \(y_K\) est d'ordre infini dans \(E(K)\). Pour revenir au groupe de Shafarevich-Tate, il s'avère que ce dernier est très difficile à calculer (d'où l'importance du théorème de Kolyvagin). Toutefois, il existe un autre groupe plus calculable, lié au groupe de Shafarevich-Tate, qui encode à la fois l'information contenue dans \(\textnormal{Ш}(E/\mathbb{Q})\) et dans \(E(\mathbb{Q})\). Il s'agit du groupe de Selmer, noté \[\textnormal{Sel}(E/\mathbb{Q}).\] Là où Kolyvagin a fait fort dans sa preuve, c'est par la méthode qu'il a employée, totalement novatrice pour l'époque. Il utilisa les points de Heegner pour construire un système vérifiant les propriétés de ce qui est désormais appelé un "système d'Euler". À l'aide de ce système d'Euler, Kolyvagin a notamment montré que le groupe de Selmer \(\textnormal{Sel}(E/K)_p\) est cyclique, engendré par un certain élément \(\delta(y_K)\). Pour l'anecdote, avec l'axiomatisation de la théorie des systèmes d'Euler entreprise par B. Mazur et K. Rubin, les systèmes d'Euler de points de Heegner, dits "systèmes d'Euler anticyclotomiques", ne s'inscrivent pas dans le cadre de la définition générale d'un système d'Euler. Pour en savoir plus sur cette (très jolie) théorie, lisez le livre de K. Rubin sur le sujet. 
</p>

<p>
En théorie d'Iwasawa des courbes elliptiques, on s'intéresse non pas à la croissance des groupes de classes dans des tours d'extensions mais plutôt à celle des groupes de Selmer. En effet, dans le monde des courbes elliptiques, le groupe de Selmer joue un rôle analogue au groupe de classes : il est l’objet arithmétique fondamental dont on étudie la croissance au sein d'une tour d'extensions. Par exemple, on peut s'intéresser au groupe de Selmer d'une courbe elliptique définie sur une \(\mathbb{Z}_p\)-extension. L'un des puissants outils utilisés est la théorie de Hodge \(p\)-adique.
</p> 
La pionnière de ce champ d'étude est [Bernadette Perrin-Riou](<https://www.imo.universite-paris-saclay.fr/~bernadette.perrin-riou/>), dont les travaux m'ont beaucoup inspiré durant mon stage de M2. Pour en savoir plus au sujet de la théorie d'Iwasawa, vous pouvez lire un des articles introductifs de [Ralph Greenberg](<https://sites.math.washington.edu//~greenber/personal.html>), dont deux sont directement accessibles un peu plus bas sur cette page.


Stage de recherche de M2 (encadré par [Denis Benois](<https://www.math.u-bordeaux.fr/~dbenoua/>))
---

- **Titre du mémoire :** Théorie d'Iwasawa des courbes elliptiques, Travaux de Kolyvagin sur les courbes elliptiques modulaires et conjecture BSD.
- **Thèmes abordés :** théorie d'Iwasawa (corps de nombres, fonctions L p-adiques, courbes elliptiques), travaux de Kolyvagin sur les courbes elliptiques modulaires, points de Heegner, systèmes d'Euler et dualité de Poitou-Tate.


Quelques ressources utiles pour découvrir les (magnifiques) maths sur lesquelles je travaille
---

- Introduction à la théorie d'Iwasawa des courbes elliptiques : [Iwasawa theory for elliptic curves, R. Greenberg](/files/Iwasawa theory for elliptic curves, Greenberg.pdf)
- Sur la théorie d'Iwasawa en général : [Iwasawa theory - Past and Present, R. Greenberg](/files/Iwasawa theory - Past and present, Greenberg.pdf)
- Sur les systèmes d'Euler : [Euler systems, K. Rubin](/files/Euler systems, Rubin.pdf)
- Travaux de Kolyvagin sur les courbes elliptiques modulaires : [Kolyvagin's work on modular elliptic curves, B. H. Gross](/files/Kolyvagin's work on modular elliptic curves, Gross.pdf)
- Pour lire les premières briques de ce qui deviendra les "déformations" : [A modular construction of unramified p-extensions of Q(μp), K. A. Ribet](/files/A modular construction of unramified p-extensions of Q(μ_p), Ribet.pdf)
- Construction des fonctions L p-adiques : [On p-adic analogues of the conjectures of Birch and Swinnerton-Dyer, B. Mazur, J. Tate & J. Teitelbaum](/files/On p-adic analogues of the conjectures of Birch and Swinnerton-Dyer, Mazur.pdf)
- Preuve de la formule de Gross-Zagier : [Heegner points and derivatives of L-series, B. H. Gross & D. B. Zagier](/files/Heegner points and derivatives of L-series, Gross.pdf)