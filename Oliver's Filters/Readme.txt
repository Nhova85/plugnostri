O L I V E R 's   F I L T E R S


Qu'est ce donc?

Oliver's Filters est un ensemble de 12 filtres destin�s � Photoshop et compatibles (Painter, Paint Shop Pro,...). Ces filtres sont en 32bits et n�cessitent donc d'�tre utilis�s avec des logiciels �galement en 32bits. Ces filtres sont compatibles avec Windows 3.xx (avec Win32s), Windows 95/98 et Windows NT.

Avant toute chose, je vous remercie sinc�rement d'utiliser Oliver's Filters. N'h�sitez pas � le distribuer � vos amis, � l'envoyer vers des BBS, sites FTP,...bref � le faire connaitre. Merci.

Oliver's Filters est un FREEWARE donc 100% gratuit mais si vous l'appr�ciez vraiment, un petit cadeau est toujours la bienvenue... :-)

Ces filtres ont �t� cr��s avec Filter Factory un plug-in livr� sur le CD de Photoshop permettant de cr�er vos propres filtres. Vous avez maintenant �galement acc�s aux sources de ces filtres. Vous pouvez les modifier, les utiliser � votre guise mais il est strictement interdit des les utiliser � des fins commerciales. De m�me, si vous cr�ez des filtres � partir mes sources modifi�es ou am�lior�es, veuillez s'il vous plait m'en faire part. Ne copiez pas simplement mes filtres juste en mettant votre nom � la place du mien, ce serait ridicule.

J'ai essay� de cr�er un manuel aussi complet et d�taill� que possible, vous permettant ainsi d'exploiter au mieux mes filtres. Si vous trouvez d'autres utilisations possibles de mes filtres, n'h�sitez pas � m'en faire part, je les ajouterai imm�diatement au manuel accompagn�s de vos coordonn�es.

J'esp�re que vous prendrez plaisir � lire ce manuel et bon amusement! 

Si vous avez des remarques, questions ou simplement un avis � donner, voici mes coordonn�es:

Vanaschen Olivier 
Rue Franz Scherrer 58/4 
B-4720 La Calamine 
Belgique 
       
E-Mail: olivier.vanaschen@skynet.be ou webmaster@infographie-fr.com 
ICQ/UIN: 1433374 

Infographie-fr.com: Le site des infographistes francophones: 
http://www.infographie-fr.com



Description des filtres

Contraste S�lectif

Contraste S�lectif est un filtre permettant d'ajouter s�lectivement du contraste � une image � partir des couleurs de bases (rouge, vert, bleu ou RGB en anglais). En pratique, il permet, par exemple, de rendre plus bleue la teinte de la mer d'une image ou encore de rendre plus vert le feuillage d'un arbre sans pour autant faire une s�lection ou modifier le reste de cette image.

D�grad�s Circulaires

Ce filtre permet de cr�er toutes sortes de d�grad�s circulaires un peu � l'instar de KPT Gradient Designer. De nombreux param�tres permettent d'influer sur le r�sultat final. Les d�grad�s sont quasi illimit�s en nombre car les combinaisons de param�tres sont elles aussi quasi illimit�es. Ce filtre vous r�serve encore bien des surprises!

Lavande

Ce filtre transforme la teinte g�n�rale de l'image et donne � celle-ci des couleurs plut�t bleues et jaunes.

Lavande 2

Ce filtre transforme �galement la teinte g�n�rale de l'image et mais donne � celle-ci des couleurs plut�t jaunes et bleues.

Rayons de soleil

Ce filtre permet de simuler assez facilement les rayons du soleil, effet parasite, parfois artistique, apparaissant sur certaines photos prises en contre-jour. De nombreux param�tres sont disponibles.

Tabac

Ce filtre permet de donner un aspect vieux aux images tr�s facilement tout en ayant la possibilit� d'ajouter plus de rouge ou de jaune � l'image.

Grain Artistique

Ce filtre permet d'ajouter du grain � l'image mais non pas uniform�ment comme le font les autres filtres mais ind�pendamment du rouge, du vert et du bleu. L'effet produit est assez unique et sp�cial, je pense.

Halo

Ce filtre permet de cr�er toutes sortes de d�grad�s en forme de halos. Les 4 param�tres permettent pas mal de possibilit�s. Ce filtre peut servir de base � des effets plus complexes.

Rouge/Vert

Ce filtre modifie la teinte originale de l'image pour lui donner des couleurs rouges et vertes.

Toile d'Araign�e

Ce filtre permet de cr�er une sorte de toile d'araign�e, tout simplement. Plus vous augmentez l'intensit�, moins la toile comportera de carreaux. Bien utilis�, ce filtre permet m�me de cr�er des textures de pierres circulaires.

Tunnel

Ce filtre est un d�riv� de "Toile d'Araign�e" et permet de cr�er des effets de tunnel assez psych�d�liques mais assez r�ussi je trouve. Les 2 param�tres permettent pas mal de fantaisies.

Vert/Rouge

Ce filtre modifie �galement la teinte originale de l'image pour lui donner des couleurs vertes et rouges.



Tips

- Pour le filtre " D�grad�s Circulaires", d�butez de pr�f�rence avec une image noire ou du moins tr�s sombre. Les r�sultats n'en seront que plus probants. 

- Les filtres "Lavande" et "Lavande 2" donnent de meilleurs r�sultats avec des images tr�s color�es.

- Pour le filtre "Rayons de Soleil", l'utilisation de s�lections progressives peut rendre de tr�s bons r�sultats.

- Pour amplifier encore l'effet du filtre "Tabac", ajoutez une texture � l'image. L'effet "vieux" sera encore plus accentu�!

- La pr�visualisation du filtre "Halo" est bien plus sombre que le r�sultat final, s�rement un petit bug mais je n'ai pas r�ussi � le corriger pour l'instant. D�sol�.

- Les filtres "Rouge/Vert" et "Vert/Rouge" donnent de meilleurs r�sultats avec des images tr�s color�es.

- Les filtres "Toile d'Araign�e" et "Tunnel" se superposent tr�s bien.

- Essayez la plupart des filtres sur des images carr�es, le r�sultat est souvent tr�s convaincant.

- Essayez de nombreuses combinaisons de filtres et de param�tres et n'h�sitez pas � exp�rimenter chaque id�e qui vous passe par la t�te.



Sources

Contraste S�lectif

R: r+ctl(0)%sub(r,g,0)
G: g+ctl(1)%sub(g,b,0)
B: b+ctl(2)%sub(b,r,0)

D�grad�s Circulaires

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

Toile d'Araign�e 

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




