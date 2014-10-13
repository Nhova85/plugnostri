O L I V E R 's   F I L T E R S


Qu'est ce donc?

Oliver's Filters est un ensemble de 12 filtres destinés à Photoshop et compatibles (Painter, Paint Shop Pro,...). Ces filtres sont en 32bits et nécessitent donc d'être utilisés avec des logiciels également en 32bits. Ces filtres sont compatibles avec Windows 3.xx (avec Win32s), Windows 95/98 et Windows NT.

Avant toute chose, je vous remercie sincèrement d'utiliser Oliver's Filters. N'hésitez pas à le distribuer à vos amis, à l'envoyer vers des BBS, sites FTP,...bref à le faire connaitre. Merci.

Oliver's Filters est un FREEWARE donc 100% gratuit mais si vous l'appréciez vraiment, un petit cadeau est toujours la bienvenue... :-)

Ces filtres ont été créés avec Filter Factory un plug-in livré sur le CD de Photoshop permettant de créer vos propres filtres. Vous avez maintenant également accès aux sources de ces filtres. Vous pouvez les modifier, les utiliser à votre guise mais il est strictement interdit des les utiliser à des fins commerciales. De même, si vous créez des filtres à partir mes sources modifiées ou améliorées, veuillez s'il vous plait m'en faire part. Ne copiez pas simplement mes filtres juste en mettant votre nom à la place du mien, ce serait ridicule.

J'ai essayé de créer un manuel aussi complet et détaillé que possible, vous permettant ainsi d'exploiter au mieux mes filtres. Si vous trouvez d'autres utilisations possibles de mes filtres, n'hésitez pas à m'en faire part, je les ajouterai immédiatement au manuel accompagnés de vos coordonnées.

J'espère que vous prendrez plaisir à lire ce manuel et bon amusement! 

Si vous avez des remarques, questions ou simplement un avis à donner, voici mes coordonnées:

Vanaschen Olivier 
Rue Franz Scherrer 58/4 
B-4720 La Calamine 
Belgique 
       
E-Mail: olivier.vanaschen@skynet.be ou webmaster@infographie-fr.com 
ICQ/UIN: 1433374 

Infographie-fr.com: Le site des infographistes francophones: 
http://www.infographie-fr.com



Description des filtres

Contraste Sélectif

Contraste Sélectif est un filtre permettant d'ajouter sélectivement du contraste à une image à partir des couleurs de bases (rouge, vert, bleu ou RGB en anglais). En pratique, il permet, par exemple, de rendre plus bleue la teinte de la mer d'une image ou encore de rendre plus vert le feuillage d'un arbre sans pour autant faire une sélection ou modifier le reste de cette image.

Dégradés Circulaires

Ce filtre permet de créer toutes sortes de dégradés circulaires un peu à l'instar de KPT Gradient Designer. De nombreux paramètres permettent d'influer sur le résultat final. Les dégradés sont quasi illimités en nombre car les combinaisons de paramètres sont elles aussi quasi illimitées. Ce filtre vous réserve encore bien des surprises!

Lavande

Ce filtre transforme la teinte générale de l'image et donne à celle-ci des couleurs plutôt bleues et jaunes.

Lavande 2

Ce filtre transforme également la teinte générale de l'image et mais donne à celle-ci des couleurs plutôt jaunes et bleues.

Rayons de soleil

Ce filtre permet de simuler assez facilement les rayons du soleil, effet parasite, parfois artistique, apparaissant sur certaines photos prises en contre-jour. De nombreux paramètres sont disponibles.

Tabac

Ce filtre permet de donner un aspect vieux aux images très facilement tout en ayant la possibilité d'ajouter plus de rouge ou de jaune à l'image.

Grain Artistique

Ce filtre permet d'ajouter du grain à l'image mais non pas uniformément comme le font les autres filtres mais indépendamment du rouge, du vert et du bleu. L'effet produit est assez unique et spécial, je pense.

Halo

Ce filtre permet de créer toutes sortes de dégradés en forme de halos. Les 4 paramètres permettent pas mal de possibilités. Ce filtre peut servir de base à des effets plus complexes.

Rouge/Vert

Ce filtre modifie la teinte originale de l'image pour lui donner des couleurs rouges et vertes.

Toile d'Araignée

Ce filtre permet de créer une sorte de toile d'araignée, tout simplement. Plus vous augmentez l'intensité, moins la toile comportera de carreaux. Bien utilisé, ce filtre permet même de créer des textures de pierres circulaires.

Tunnel

Ce filtre est un dérivé de "Toile d'Araignée" et permet de créer des effets de tunnel assez psychédéliques mais assez réussi je trouve. Les 2 paramètres permettent pas mal de fantaisies.

Vert/Rouge

Ce filtre modifie également la teinte originale de l'image pour lui donner des couleurs vertes et rouges.



Tips

- Pour le filtre " Dégradés Circulaires", débutez de préférence avec une image noire ou du moins très sombre. Les résultats n'en seront que plus probants. 

- Les filtres "Lavande" et "Lavande 2" donnent de meilleurs résultats avec des images très colorées.

- Pour le filtre "Rayons de Soleil", l'utilisation de sélections progressives peut rendre de très bons résultats.

- Pour amplifier encore l'effet du filtre "Tabac", ajoutez une texture à l'image. L'effet "vieux" sera encore plus accentué!

- La prévisualisation du filtre "Halo" est bien plus sombre que le résultat final, sûrement un petit bug mais je n'ai pas réussi à le corriger pour l'instant. Désolé.

- Les filtres "Rouge/Vert" et "Vert/Rouge" donnent de meilleurs résultats avec des images très colorées.

- Les filtres "Toile d'Araignée" et "Tunnel" se superposent très bien.

- Essayez la plupart des filtres sur des images carrées, le résultat est souvent très convaincant.

- Essayez de nombreuses combinaisons de filtres et de paramètres et n'hésitez pas à expérimenter chaque idée qui vous passe par la tête.



Sources

Contraste Sélectif

R: r+ctl(0)%sub(r,g,0)
G: g+ctl(1)%sub(g,b,0)
B: b+ctl(2)%sub(b,r,0)

Dégradés Circulaires

R: r+ctl(0)%(r/g+m)*(ctl(3)/10)
G: r+ctl(1)%(g/b+m)*(ctl(4)/10)
B: r+ctl(2)%(b/r+m)*(ctl(5)/10)

Lavande

R: r
G: g
B: g

Lavande 2

R: g
G: g
B: r

Rayons de Soleil

R: r+d%ctl(0)+m%ctl(3)
G: g+d%ctl(1)+m%ctl(4)
B: b+d%ctl(2)+m%ctl(5)

Tabac

R: r+ctl(0)
G: r+ctl(1)
B: r

Grain Artistique

R: g+rnd(r,255)%ctl(0)
G: g+rnd(r,255)%ctl(1)
B: g+rnd(r,255)%ctl(2)

Halo

R: (ctl(0)*m)/(ctl(3)+10)
G: (ctl(1)*m)/(ctl(3)+10)
B: (ctl(2)*m)/(ctl(3)+10)

Rouge/Vert

R: g
G: r
B: r

Toile d'Araignée 

R: r-m%10*d%ctl(0)
G: g-m%10*d%ctl(0)
B: b-m%10*d%ctl(0)

Tunnel 

R: r-m%(ctl(1)%256)*(d%ctl(0))
G: g-m%(ctl(1)%256)*(d%ctl(0))
B: b-m%(ctl(1)%256)*(d%ctl(0))

Vert/Rouge

R: r
G: g
B: g




Merci d'utiliser Oliver's Filters




