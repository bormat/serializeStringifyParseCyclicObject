warning: Array became object so the length attribute is not recalculate if you don't use push,
the next version will resolve this.

if you don't want losed your classes in object add an attribute serializationName to the object or on his prototype. constructor have to be public.

Attention les tableaux deviennent des objets l'attribut length n'est plus recalculer lors des modification sans utilisation de push. Peut être résolus dans une version ultérieur.

Si vous voulez garder les classe de vos objet il faut stoké le nom de votre classe publique dans l'attribut serializationName de votre objet.votre Classe constructeur doit avoir un prototype mettez le directement dedans 