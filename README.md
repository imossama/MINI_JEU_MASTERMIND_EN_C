# Jeu Mastermind en C

Le Jeu Mastermind est une application console développée en langage C qui simule le jeu de société Mastermind. Dans ce jeu, un joueur doit deviner une combinaison de chiffres en un nombre limité d'essais.

## Table des Matières

- [Comment Jouer](#comment-jouer)
- [Captures d'Écran](#captures-décran)
- [Exécution](#exécution)
- [Améliorations Futures](#améliorations-futures)
- [Crédits](#crédits)

## Comment Jouer <a name="comment-jouer"></a>

Au lancement du programme, le joueur est accueilli par un menu principal offrant plusieurs options :

1. **Jouer :** Commencer une partie de Mastermind.
2. **Comment jouer ? :** Afficher les instructions pour jouer au jeu.
3. **Son :** Activer ou désactiver le son de l'application.
4. **Quitter :** Fermer le jeu.

Si l'option "Jouer" est choisie, le joueur peut sélectionner le niveau de difficulté : niveau 1 ou niveau 2. Dans le niveau 1, les chiffres ne peuvent pas être répétés, tandis que dans le niveau 2, chaque chiffre peut être utilisé jusqu'à deux fois. Le joueur 1 entre une combinaison secrète de 5 chiffres, que le joueur 2 doit deviner en un nombre limité d'essais.

Après chaque essai, le programme affiche la réponse en utilisant les symboles suivants :

- [+] : Chiffre bien placé.
- [-] : Chiffre mal placé.
- [&nbsp;&nbsp;] : Chiffre inexistant.

Après 10 essais, le joueur 2 peut utiliser l'option Joker pour obtenir un chiffre de la combinaison secrète du joueur 1, mais cela entraîne une pénalité de 3 essais.

## Captures d'Écran <a name="captures-décran"></a>

### Menu Principal
![Menu Principal](https://user-images.githubusercontent.com/119759894/230787611-d0322db6-c310-4947-954b-1041abd677f0.png)

### Instructions du jeu
![Instructions](https://user-images.githubusercontent.com/119759894/230787635-47ef8829-86e3-48e2-b45d-80341665a564.png)

### Niveaux de Difficulté
![Screenshot 2024-08-12 142728](https://github.com/user-attachments/assets/b738c3e8-f637-400c-b802-ad7893ec8089)

### Début de la Partie
![Début de la Partie](https://user-images.githubusercontent.com/119759894/230787676-83365cba-98ee-4097-8131-4e5f37237dc0.png)

### Fin de la Partie
![Fin de la Partie](https://user-images.githubusercontent.com/119759894/230787753-992210e1-570e-4717-a0ae-b8d75ea34b6c.png)

## Exécution <a name="exécution"></a>

Le programme peut être exécuté sur un terminal ou une invite de commande. Il a été développé et testé sur Windows.

1. Ouvrir un terminal ou une invite de commande.
2. Naviguer vers le répertoire contenant le fichier `Mastermind.c`.
3. Compiler le programme avec la commande `gcc Mastermind.c -o Mastermind`.
4. Exécuter le programme avec la commande `./Mastermind`.

## Améliorations Futures <a name="améliorations-futures"></a>

Voici quelques améliorations envisagées pour les prochaines versions du Jeu de Mastermind :

- Ajout de niveaux de difficulté supplémentaires.
- Intégration d'une fonctionnalité pour enregistrer et comparer les scores.
- Traduction du jeu en anglais.

## Crédits <a name="crédits"></a>

Ce programme est libre de droit et peut être utilisé ou modifié à des fins non commerciales.
