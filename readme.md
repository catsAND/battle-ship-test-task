# Battle ship test task

Preferably develop following task in PHP. Make sure code is posted in gitgub or binbucket public repo.

1. UI implementation is not important. Use the simpliest and the easiest way you can. It will not play any role in evaluation, apart from evaluating your general ability to implement a frontend part it needed.
1. Focus of this assignment is server side logic implementation - logic implementation on server side plays a crucial role in evaluation.
1. Let's create an onscreen grid of cells aligned within a square 10 by 10.
1. Then we set up initial battle ships - one L shaped, one I shaped and two dot shaped. Initial battle ships cannot overlap.
1. Start actual game play after any kind of user input which would simulate shots at random positions - any missed shot would indicate already hit area, any shot at any of initial ships would visually indicate that battle ship has sink (change of ship color would be fine enough).
1. Program must be able to tell that all ships have sunk and game is over.
1. Battle ships must not touch one another so there is at least a single cell between them. Any battle ship rotation must be random.
1. Multi cell battle ships (I && L) must consist of 4 cells, so there is no ambiguity of L shapes that do not look like L and I shapes of more or less than 4 cells.
