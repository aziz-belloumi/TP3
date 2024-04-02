Question :

equals() : Cette méthode compare les contenus des deux chaînes et retourne true si elles ont le même contenu (sensible à la casse), sinon elle retourne false.

equalsIgnoreCase() : Cette méthode compare les contenus des deux chaînes en ignorant la casse et retourne true si elles ont le même contenu (sans tenir compte de la casse), sinon elle retourne false.

== : Cet opérateur compare les références des deux chaînes. S'ils pointent vers le même objet en mémoire, il retourne true, sinon il retourne false. Il ne compare pas les contenus des chaînes, il compare seulement si les références sont identiques.

Différence entre ces méthodes : "equals()" et "equalsIgnoreCase()" comparent le contenu des chaînes, ce qui signifie qu'elles renverront true si le contenu est le même, indépendamment de la référence mémoire.Mais , "==" compare les références mémoire des objets. Deux chaînes ayant le même contenu peuvent pointer vers des objets différents en mémoire, donc cette méthode ne garantit pas la comparaison du contenu réel des chaînes
