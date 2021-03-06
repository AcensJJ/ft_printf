<p align="center">
    <img alt="42-lyon" src="https://user-images.githubusercontent.com/45235527/106354618-6ec65a00-62f3-11eb-8688-ba9e0f4e77de.jpg" />
</p>

# ft_printf

<img alt="Note" src="https://user-images.githubusercontent.com/45235527/96753610-698e7080-13d0-11eb-9461-d3351c9208d7.png" width="250" height="200" />

### <strong>Description</strong>

Ce projet est clair et efficace. Vous devez recoder printf. Vous aurez dès lors la possibilité de le réutiliser dans vos futurs projets.
Ce projet porte principalement sur les arguments à taille variable.


# Partie obligatoire

![Sujet](https://user-images.githubusercontent.com/45235527/96753783-a195b380-13d0-11eb-90f9-31928a4bc773.png)

- Le prototype de ft_printf devra être `int ft_printf(const char *, ...);`
- Vous devez recoder la fonction printf de la libc
- Vous ne devez pas gérer de buffer, contrairement au vrai printf
- Vous devez gérer les conversions suivantes : `cspdiuxX%`
- Vous devez gérer n’importe quelle combinaison de flags `’-0.*’` et la taille de champ
minimale avec toutes les conversions
- Votre rendu sera comparé au vrai printf
- Vous devez utiliser la commande ar pour créer votre librairie, l’utilisation de la
commande libtool est interdite
