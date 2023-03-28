# Frython - c'est comme Python, mais en Français

<p align="center">
  <img src="./logo.svg">
</p>

## Instructions de montage

Sur Unix, Linux, BSD, macOS, et Cygwin

```
./configure
make
```

Cela va créer un exécutable `frython`. Sur macOS et sur Cygwin, l'exécutable sera `frython.exe`; ailleurs cela sera juste `frython`.

## Exemple d'utilisation

Pour lancer l'interpréteur Frython, il vous suffit de faire 

```
./frython
```

Vous pouvez alors commencer à écrire votre premier code en Frython !

```
Frython 3.11.2 (heads/master-dirty:6779017766, Mar 28 2023, 12:10:04) [GCC 11.2.0] sur linux
Tape "help", "copyright", "credits" ou "license" pour plus d'informations.
>>> affiche("Coucou le monde")
Coucou le monde
```

## Conversion des mots clés et des méthodes par défaut

### Mots clés

| Anglais  | Français |
|:---------|:---------|
| as       | comme    |
| if       | si       |
| in       | dans     |
| is       | est      |
| or       | ou       |
| and      | et       |
| def      | definis  |
| del      | efface   |
| for      | pour     |
| not      | pas      |
| try      | essaie   |
| elif     | sinsi    |
| else     | sinon    |
| from     | depuis   |
| None     | Rien     |
| pass     | passe    |
| True     | Vrai     |
| with     | avec     |
| break    | casse    |
| class    | classe   |
| False    | Faux     |
| raise    | leve     |
| while    | tantque  |
| yield    | rends    |
| assert   | affirme  |
| except   | sauf     |
| global   | global   |
| import   | importe  |
| lambda   | lambda   |
| return   | retourne |
| finally  | enfin    |
| continue | continue |
| nonlocal | nonlocal |

### Méthodes

| Anglais      | Français        |
|:-------------|:----------------|
| all          | tout            |
| any          | quelconque      |
| len          | taille          |
| pow          | puissance       |
| set          | ensemble        |
| sum          | somme           |
| list         | liste           |
| next         | suivant         |
| open         | ouvre           |
| input        | saisis          |
| print        | affiche         |
| range        | intervalle      |
| round        | arrondis        |
| sorted       | trie            |
| property     | propriete       |
| reversed     | renverse        |
| enumerate    | enumere         |
| isinstance   | estinstance     |
| issubclass   | estsousclasse   |
| classmethod  | methodeclasse   |
| staticmethod | methodestatique |

## Docker

Pour une grande facilité d'utilisation, Frython est aussi disponible en tant qu'image docker, ou [marcel cederom](https://github.com/brouberol/marcel#examples), sur la [page Docker Hub de Frython](https://hub.docker.com/r/magiclemp/frython).
