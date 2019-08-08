# nancloud
 
# I- Comment Utiliser le projet
  ## I-1 Intall Django mac os

##Setup 1

###  créer un environnement virtuel

creer un dossier ouvrez le dossier dans le terminal
enauite executer les commandes suivante

```bash
$ python3 -m venv venv
```
##Setup 2: activer l'environnement virtuel

```bash
$ source venv/bin/activate
```

##Setup 3:Installer Django

```bash
$ pip3 install Django
```

Une fois django installer on va cloner le projet et lancer le projet

```bash
$ git clone https://github.com/EcoleNaN/nancloud.git

$ cd nancloud/cloudnan


```

On va installer les dependances necessaire pour le bon fonctionnement de cloud


```bash

$ pip3 install django-filer

```

Une fois l'installation est correcte alors on lance le projet

```bash
$ python3 manage.py runserver

```


En cas de soucis merci de me signaler en creant des issue. 
