# Simple-rogue-like

### Written in (Turbo) C++, but has procedural design.

Based on tutorials from
* [r/roguelikedev](https://old.reddit.com/r/roguelikedev)
* [rogueliketutorials.com/tutorials/tcod/v2/](https://rogueliketutorials.com/tutorials/tcod/v2/)

Dungeons generated using ["Drunkard Walk" algorithm](https://web.archive.org/web/20230421205845/http://www.roguebasin.com/index.php/Random_Walk_Cave_Generation).

Use 'MIE' to add/remove monsters and items, and edit details such as name, colour, damage, health regenerated, and spawn amount.



## ToDo

* Incorrect use of inheritance. Repetition of 'Entity' code in 'Monster' and 'Item' classes. Use composition instead.
