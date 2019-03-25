<img src="img/phoenix.jpg">

# -Project- The Phoenix War
> "The Phoenix war" is an role & quiz game coded in C.

![GitHub](https://img.shields.io/github/license/KyuCore/The-Phoenix-War--Project-.svg)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/KyuCore/The-Phoenix-War--Project-.svg)

## Description 

The Phoenix war is a solo role-playing game (RPG) released in 2019 by two ENST's student. It is the first released game set in the RUNETERRA fantasy universe, without any dynamic graphics, and was inspired by the [Warcraft III: The Frozen Throne mod, Defense of the Ancients](https://en.wikipedia.org/wiki/World_of_Warcraft#Starting_a_character_or_play_session) & [League of Legend](https://en.wikipedia.org/wiki/League_of_Legends).

   In The Phoenix War, players assume the role of an unseen "summoner"
that controls a "Hero" with some abilities and battle an other race.The goal is to win the power of 'The Flames Of The Phoenix'.

### Gameplay

The Phoenix war is a non-graphic game coded in C. The game consist of one game mode; there is different ways to finish the game, each hero you choose will impact the story mode. To win, the summoner have to answer correctly some questions, like a quiz... But for some Hero either you die before you start or you win by answering just one question. Ups to you to discover!

![](img/game.png)
### Rules

There is no specific rules in this game you just have to:
- Start the game (exectable file)
- Enter you name 
- Choose a race
- Try to answer all the questions (There is a score at the end xD)
- Do not die
- Enjoy it!

<strong>Note<strong>: For More Help Press 'H' key when launching the game.

### Structure and functions

Almost 540 lines of codes written in C to ensure a good user experience.
<strong>some of the used functions :<strong>

- The record screen (showing the scrore...) reading the score of the txt file and showing it on the screen...
```C
void show_record(){
system("cls");
char name[20];
float scr;
FILE *f;
f=fopen("score.txt","r");
fscanf(f,"%s%f",&name,&scr);
printf("\n\n\t\t_______________________________________________________");
printf("\n\n\t\t %s has secured the Highest Score %0.2f",name,scr);
printf("\n\n\t\t_______________________________________________________");
fclose(f);
getch();}
```

## Installation
## Contribution
### License