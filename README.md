# frogger clone in processing

> Vodka may not be the answer but it’s worth a shot

# Mechanics
- moving one tile at a time
- bonus
- smooth moving tiles and logs
- Highsocore
- Time limit (50 sec)
- score counter
### score system
| factors  | points |
| ------------- | ------------- |
| Successful forward jump | 10 points  |
| Getting a frog home  | 50 points  |
| For each remaining second  |  10 points  |
| Escorting a lady frog home |  200 points  |
| Catching a fly |  200 points  |
| Getting all 5 frogs home  |  1000 points |


# Flow diagram
!["./Flowdiagram Frogger.png"](https://raw.githubusercontent.com/imkowalski/frogger-clone-processing/main/Flowdiagram%20Frogger.png)

Classes vi kunne bruge:

car/log

- En class, som giver funktionen med at gå fra højre til venstre samt venstre
til højre. ville ikke bestemme dens fart siden det variere sig mellem biler.
Det skal bevæge sig via pixels og ikke tiles.

collision

- En class, der ville se hvor frogger kan, og ikke kan stå/hoppe. Både til de
steder, hvor Frogger ikke kan hoppe, og hvornår har dør ved at stå/ hoppe et
sted.

UI

- En class som styrede intro skærm. ville være start game og måske 1-2 player

Win condition/game controller

- En class, der tjekker om man er færdig med ens lvl. Hvilket level man er ved
  samt hvor mange liv man har tilbage.

player

- ville være om Froggers movement. At han kan ses/styres

- Er allerede blevet implementeret semi. 

# GIT TUTORIAL (til mads)

To update your local directory to the latest version
````
git pull
````

To add all the new files and changes to files, to your next push
````
git add .
````
Write a short message that describes your changes
````
git commit
````

Push your changes to github repo
````
git push origin
````

<br><br>
-------------------

# ***NO BITCHES??***
![a](https://images.start.gg/images/tournament/421471/image-47f0864a612a912f4e029a77e63ac659.jpg?ehk=GzvB%2F74b4SkWJ4hFT9gdibfoK0HQ6WRSng6gZ4SQD6A%3D&ehkOptimized=cmIY9eC%2FJFY5Z9oXaBp1raGtdvMOnTJmqzSnUZ0vBj4%3D)
-------------------
