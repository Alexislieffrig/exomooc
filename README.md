# Info-F-101: Exercices mooc avec l'ULB

![N|Solid](https://fundit.fr/sites/default/files/actors/1456-universite-libre-bruxelles-ulb.jpg)

![N|Solid](https://theme.zdassets.com/theme_assets/504801/469038bd4c780a92818fad61649d3aca5cc90d36.png)

## Présentation générale:
### Les exercices mooc
>L’objectif des exercices mooc est de comprendre la programmation étape par étape jusqu'a atteindre un niveau basique de la prorammation.

## Les différents niveaux:
>les exercices se partagent en 6 niveaux (modules) différents:
 - module 1 : Bienvenue dans l'environement python
 - module 2 : Python comme machine à calculer et à écrire
 - module 3 : Apréhention des instructions
 - module 4 : Créations d'outils avec les fonctions 
 - module 5 : Séquences de données pour jouer ou travailler 
 - module 6 : Les ensembles et dictionnaires 
 
# Commençons les explications du module 1:
>Les seuls buts de cet exercice sont de vérifier que vous avez accès à  l'exerciseur UpyLaB et de vous donner un premier contact avec cet outil.

exercice du module 1:

- Écrire un programme qui affiche « Bonjour UpyLaB ! » grâce à l’instruction:
print("Bonjour UpyLaB !")

solution:

      print("Bonjour UpyLaB !")

# Expliations module 2:

>Nous allons entamer l’apprentissage de la programmation et du langage Python. Dans ce module, nous apprendrons comment faire de l’arithmétique et manipuler des textes. Nous verrons aussi comment facilement faire des dessins géométriques.

##Exercice 1) 

Le but de cet exercice est de vérifier que vous savez définir des variables, et leur affecter des valeurs des différents types rencontrés dans le cours.

###Écrire un programme qui assigne :

- la valeur entière 36 à la variable x ;

- la valeur entière résultat de 36 fois 36 à la variable produit ;

- la valeur entière résultat de la division entière de 36 par 5 à la variable div_entiere ;

- la valeur entière résultat de 15 exposant 15 à la variable expo ;

- la valeur float 3.14159 à la variable pi ;

- la valeur chaîne de caractères "Bonjour" à la variable mon_texte.


solutuion:

      la valeur entière 36 à la variable x 
      x = 36
      la valeur entière résultat de 36 fois 36 à la variable produit ;
      produit = (x*x)
      la valeur entière résultat de la division entière de 36 par 5 à la variable div_entiere ;
      div_entiere = (36//5)
      la valeur entière résultat de 15 exposant 15 à la variable expo ;
      expo = (15**15)
      la valeur float 3.14159 à la variable pi ;
      pi = 3.14159
      la valeur chaîne de caractères "Bonjour" à la variable mon_texte.
      mon_texte = "Bonjour"

## Exercice 2)

###Écrire un programme qui imprime (donc grâce à la fonction print):

la moyenne arithmétique de deux nombres de type float lus en entrée (c'est-à-dire grâce à des appels à la fonction input) .

On rappelle que la moyenne arithmétique de deux nombres a et b est égale à {a+b}/{2}.

solution:

      x = int(input())
      y = int(input())
      print((x+y)/2)

## Exercice 3)

###Écrire un programme qui lit des valeurs de type float:
pour a, b et c et qui affiche la valeur de d vérifiant l'égalité {a}/{b} = {c}/{d}.

solution:

    a = float(input())
    b = float(input())
    c = float(input())
    d = (b*c)/a
    print(d)

##Exercice 4)

###Écrire un programme qui lit:

deux valeurs entières x et y strictement positives suivies de deux valeurs réelles (float) z et t, et qui affiche les valeurs des expressions suivantes, chacune sur une nouvelle ligne

x - y

x + z

z + t

x.z (soit le produit de x et de z)

({x/2)

x/(y + 1)

(x^(1/2)) (soit x à la puissance d'exposant -1/2)

solution: 

    x = int(input())
    y = int(input())
    z = float(input())
    t = float(input())

    print(x-y)
    print(x+z)
    print(z+t)
    print(x*z)
    print(x/2)
    print(x/(y+1))
    print(((x+y)*z)/(4*x))
    print(x**(-(1/2)))

##Exercice 5)

###Écrire un programme affichant les quatre lignes suivantes :

    Hello World
    Aujourd'hui
    C'est "Dommage !"
    Hum \o/

solution:

    print("Hello World")
    print("Aujourd'hui")
    print("C'est \"Dommage !\"")
    print("Hum \o/")

##Exercice 6)

###Écrire un programme qui imprime la valeur du volume d’une sphère de rayon r, float lu en entrée:

On rappelle que le volume d’une sphère de rayon r est donné par la formule :
(4/3).pi.r^(3)

solution: 

    from math import pi
    r = float(input())

    volume_sphere = ((4/3)*pi*(r**(3)))
    print(volume_sphere)


#Explication module 3:

>Nous voici arrivés à la troisième phase d’apprentissage en ce qui concerne l’instruction if. Dans l’activité qui va suivre, nous vous proposons d’utiliser notre exerciseur UpyLaB pour tester de manière autonome plusieurs exercices qui demandent d’utiliser l’instruction if.

##Exercice 1)

###Écrire un programme qui lit:
3 nombres entiers, et qui, si au moins deux d’entre eux ont la même valeur, imprime cette valeur (le programme n’imprime rien dans le cas contraire).

solution: 

    x = int(input())
    y = int(input())
    z = int(input())

    if x==z:
        print(x)
    elif x==y:
        print(x)
    elif y==z:
        print(y)

##Exercice 2)

###Écrire un programme qui, si temperature (entier lu sur input correspondant à la température maximale prévue pour aujourd’hui) est strictement supérieur à 0, teste si temperature est inférieur ou égal à 10:
Auquel cas il imprime le texte :

    Il va faire frais.

Et qui, si temperature n’est pas supérieur à 0, imprime le texte :

    Il va faire froid.

Dans les autres cas, le programme n’imprime rien.

solution:

    temperature = int(input())

    if temperature > 0:
        if temperature <= 10:
            print("Il va faire Frais")
    elif temperature < 0:
        print("Il va faire froid")
    else:
        None

##Exercice 3)

###Écrire un programme qui lit trois entiers a, b et c en input. Ensuite :

si l’entier c est égal à 1, alors le programme affiche la valeur de a + b ;

si c vaut 2, alors le programme affiche la valeur de a - b ;

si c est égal à 3, alors l’output sera la valeur de a.b (produit de a par b) ;

enfin, si la valeur 4 est assignée à la variable c, alors le programme affiche la valeur de a^2 + a.b ;

et si c contient une autre valeur, le programme affiche le message 

    Erreur.

solution:

    a = int(input())
    b = int(input())
    c = int(input())

    if c == 1:
        print(a+b)
    elif c == 2:
        print(a-b)
    elif c == 3:
        print(a*b)
    elif c == 4:
        print((a**b)+(a*b))
    elif c != 1 or 2 or 3 or 4:
        print("Erreur.")

autre solution:

    a = int(input())
    b = int(input())
    c = int(input())

    if c == 1:
        print(a+b)
    elif c == 2:
        print(a-b)
    elif c == 3:
        print(a*b)
    elif c == 4:
        print((a**2) + (a*b))
    else: 
        print("Erreur")


















